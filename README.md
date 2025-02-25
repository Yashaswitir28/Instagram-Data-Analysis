# Instagram-Data-Analysis
# Instagram Clone Database Queries

This repository contains SQL queries for analyzing data from a simulated Instagram clone database. The database schema includes tables for users, photos, comments, likes, follows, tags, and photo_tags.

## Database Schema

The database consists of the following tables:

-   **users**: Stores user information (id, username, created_at).
-   **photos**: Stores photo information (id, image_url, user_id, created_at).
-   **comments**: Stores comments on photos (id, comment_text, user_id, photo_id, created_at).
-   **likes**: Stores likes on photos (user_id, photo_id, created_at).
-   **follows**: Stores follow relationships between users (follower_id, followee_id, created_at).
-   **tags**: Stores hashtags (id, tag_name, created_at).
-   **photo_tags**: Junction table linking photos and tags (photo_id, tag_id).

## Setup

1.  **Create the database:**
    ```sql
    CREATE DATABASE ig_clone;
    USE ig_clone;
    ```
2.  **Create the tables:** (See the provided SQL script for table creation statements.)
3.  **Insert the data:** (See the provided SQL script for INSERT statements.)

## Usage

You can use these queries to analyze and gain insights from the Instagram clone database. Feel free to modify and extend these queries to suit your specific analysis needs.

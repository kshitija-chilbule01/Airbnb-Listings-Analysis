# Airbnb Listings Analysis 🛋️

![Airbnb](https://github.com/user-attachments/assets/627af6b8-bce9-4ad6-94d4-a6551151d86d)

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets Used](#datasets-used)
- [Listings Dataset Dictionary](#listings-dataset-dictionary)
- 


## 📌Project Overview
This project aims to analyze Airbnb listings in Paris to understand the impact of recent regulatory changes on the short-term rental market. The analysis leverages data from over 250,000 listings across 10 major global cities, including Paris, as well as approximately 5 million guest reviews.

Through this exploratory analysis, we investigate how these new regulations are influencing Airbnb activity in terms of listing availability, pricing strategies, guest experiences, and host behavior.

## 📂Datasets Used
The project is based on two main datasets:

```listings.csv``` – Contains detailed information about Airbnb listings.

```reviews.csv``` – Includes guest review data for each listing.

## 📖Listings Dataset Dictionary
| **Column Name**               | **Description**                                                                 |
|------------------------------|---------------------------------------------------------------------------------|
| `listing_id`                 | Unique identifier for the listing                                              |
| `name`                       | Name/title of the listing                                                      |
| `host_id`                    | Unique ID of the host                                                          |
| `host_since`                 | Date the host joined Airbnb                                                    |
| `host_location`              | Location where the host is based                                               |
| `host_response_time`         | Estimated response time of the host                                            |
| `host_response_rate`         | Percentage of messages responded to by the host                                |
| `host_acceptance_rate`       | Percentage of accepted booking requests                                        |
| `host_is_superhost`          | Whether the host is a Superhost (Yes/No)                                       |
| `host_total_listings_count`  | Total number of listings the host manages                                      |
| `host_has_profile_pic`       | Whether the host has a profile picture                                         |
| `host_identity_verified`     | Whether the host's identity is verified                                        |
| `neighbourhood`              | Neighborhood the listing is located in                                         |
| `district`                   | Administrative district of the listing                                         |
| `city`                       | City where the listing is based                                                |
| `latitude`                   | Latitude of the listing                                                        |
| `longitude`                  | Longitude of the listing                                                       |
| `property_type`              | Type of property (e.g., Apartment, House)                                      |
| `room_type`                  | Type of room offered (e.g., Private room, Entire home)                         |
| `accommodates`              | Number of guests the listing can host                                          |
| `bedrooms`                   | Number of bedrooms available                                                   |
| `amenities`                  | List of amenities provided                                                     |
| `price`                      | Nightly price (in local currency)                                              |
| `minimum_nights`             | Minimum nights per booking                                                     |
| `maximum_nights`             | Maximum nights allowed per booking                                             |
| `review_scores_rating`       | Overall rating out of 100                                                      |
| `review_scores_accuracy`     | Accuracy score (out of 10)                                                     |
| `review_scores_cleanliness`  | Cleanliness score (out of 10)                                                  |
| `review_scores_checkin`      | Check-in experience score (out of 10)                                          |
| `review_scores_communication`| Communication score with host (out of 10)                                      |
| `review_scores_location`     | Location rating (out of 10)                                                    |
| `review_scores_value`        | Value-for-money rating (out of 10)                                             |
| `instant_bookable`           | Whether listing supports instant booking (Yes/No)                              |

## 📖Reviews Dataset Dictionary 
| **Field**       | **Description**      |
|-----------------|----------------------|
| `listing_id`    | Listing ID           |
| `review_id`     | Review ID            |
| `date`          | Review date          |
| `reviewer_id`   | Reviewer ID          |

# Job Offer Comparison App

This is a collaborative project undertaken by students enrolled in the Online Master's Degree of Computer Science (OMSCS) program at the Georgia Institute of Technology, as part of the course "CS6300 Software Development Process."

## Background

Upon graduation, a student faces the task of finding a new job. However, comparing job offers can be complex due to various factors such as benefits, location, and other non-salary aspects. Hence, there is a need for a simple, single-user offer comparison app.

## Requirements

The detailed requirements for this project can be found on [this page](https://docs.google.com/document/d/1w9zxYYCPlE4AgCw6RKFky7PBVxfjVJTs/edit?usp=sharing&ouid=101210288575378616443&rtpof=true&sd=true).

## Key Features

- **Development Platform:** The app is built on the Android platform.
- **Minimum API Level:** The minimum API level for the app is "Pixel 6, API 33".
- **Android SQLite:** Utilize Android SQLite to store job listings and comparison settings directly on the user's mobile device. The application undergoes testing in a clean-checkout state and with a new or cleared Android Virtual Device (AVD) to ensure compatibility with various environments.
- **EditText:** Enable users to input job details using EditText fields.
- **Customized Comparator:** Implement a customized comparator class to facilitate comparison of job offers based on user-defined weights.
- **RecyclerView:** Utilize RecyclerView to dynamically display job offers in the app interface.
- **Checkbox Buttons:** Incorporate radio buttons to allow users to select job offers from the RecyclerView and view their details.

## User Manual

**Main Menu**

- This is the entry point for the user to get access to different components

<img width="286" alt="image" src="https://github.com/Sol2023/job_compare/assets/92194263/7e38a853-9347-42e5-88bc-6bbaa461e0f9">

**Current Job Information**

- It is the palace where you can check current Job information, also, you could update your current Job information if there are any changes happened.

<img width="282" alt="image" src="https://github.com/Sol2023/job_compare/assets/92194263/a8bfec46-233b-49d3-a7df-44fd532d0b3f">


**New Job Offer**

- Here it allows you to add a new offer, and you are able to compare the new job offer with current job, the app will calculate the score based on the given factors

<img width="283" alt="image" src="https://github.com/Sol2023/job_compare/assets/92194263/63e2cf2c-7ff6-42f8-a8a0-951d979422c0">

**Job Comapre**

- Here you can see a list of job offers, and you are able to choose two jobs 

<img width="285" alt="image" src="https://github.com/Sol2023/job_compare/assets/92194263/76338bed-0089-4f34-bcb5-d85968ec2c72">

**Job Compare Result**

- It will show the result of two selected jobs, or the result of new job and current job.

<img width="287" alt="image" src="https://github.com/Sol2023/job_compare/assets/92194263/c919ebc5-43f7-409a-870f-87d7eb92f9e7">

**Comparison Weight**

- It is a place to modify the weigth of each factor, which will reflect on the final score

<img width="281" alt="image" src="https://github.com/Sol2023/job_compare/assets/92194263/da5bf8f8-4f01-4837-83da-b2c7bde13d48">


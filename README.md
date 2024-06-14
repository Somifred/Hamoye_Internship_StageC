File created with Google Colaboratory
Develop a Python script to scrape job listings from the "Wuzzuf" website. The script should extract specified features from each job listing using the requests and BeautifulSoup libraries, handle pagination to traverse multiple pages of listings, and save the extracted data into a CSV file on Google Drive.

By implementing this script, we aim to automate the process of scraping job listings from "Wuzzuf", extracting detailed job information, and storing it in a structured format for further analysis or usage. This solution will facilitate easy and efficient data collection from the "Wuzzuf" website.


Extracted Features and Description
Job Title: The name or designation of the job position being advertised.
Company Name: The name of the organization or business that is offering the job.

Location: The physical place where the job is located. This feature will be further parsed into: Country: The country where the job is based. City: The city within the country where the job is located. Area: A more specific locality or region within the city.

Workplace Type: The type of work environment or location for the job. It may specify whether the job is onsite, remote, or hybrid.

Career Level: The level of seniority or experience required for the job. This indicates whether the job is for entry-level candidates, experienced professionals, or senior executives.

Years of Experience: The amount of professional experience required or preferred for the job. This can help candidates assess if they meet the experience criteria for the position.

Job Category: The functional area or industry sector to which the job belongs. This categorizes the job based on the type of work and the skills required.

Job Type: The nature of the job in terms of employment status. This specifies whether the job is full-time, part-time, contract-based, or internship.

Date Posted: The date on which the job listing was posted or published. This helps in identifying the recency of the job posting.

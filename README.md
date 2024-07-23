# LinkedIn People Scraper

Interested in using this scraper? Get it here: [LinkedIn People Scraper](https://apify.com/pratikdani/linkedin-people-profile-scraper). Scrape LinkedIn people profiles and extract complete information in bulk.

## Features

**Data Export and Integration:** Once the scraping process is complete, you can easily export the extracted data in various formats such as JSON, CSV, or Excel. You can select the fields you want, allowing for seamless integration with other tools and platforms for further analysis and utilization.

**Automatic Retry and Error Handling:** In case of temporary issues like network failures or timeouts, the actor has built-in automatic retry functionality. It intelligently handles errors to ensure a smooth and uninterrupted scraping experience.

**Ability to Resume Last Failed Runs:** In case of unexpected errors, you can simply go to the actor's last run page and click on the 'Resurrect' button to resume the last scraping progress.

## Integrations

You can use [Make](https://www.make.com/en/register) to integrate the LinkedIn People scraper with any other SaaS platform by designing your own automation flows.

## Sample Output

Here is a sample output of this actor:

```json
{
  "about": "As a data scientist at Accenture, I develop the job profile accelerator platform, a…",
  "avatar": "https://media.licdn.com/dms/image/D4D03AQHz_XLbNEO4Og/profile-displayphoto-shrink_200_200/0/1674741828293?e=2147483647&v=beta&t=s3L9a6umHtxmy_cnPsSI5HopZ677mDahOe0w3-Jkm0s",
  "certifications": [
    {
      "meta": "Issued Apr 2024Credential ID E36GWDBZ6D7USee credential",
      "subtitle": "DeepLearning.AI",
      "title": "Generative AI with Large Language Models"
    },
    {
      "meta": "Issued Apr 2024Credential ID KH23BXN9PZL8See credential",
      "subtitle": "University of Glasgow",
      "title": "Generative Pre-trained Transformers (GPT)"
    },
    {
      "meta": "Issued Apr 2024Credential ID YBZK86BYWDP4See credential",
      "subtitle": "Coursera",
      "title": "Prompt Engineering Generative AI for Marketing & Advertising"
    },
    {
      "meta": "Issued Aug 2023Credential ID QWVWEPQCTCP4See credential",
      "subtitle": "Google",
      "title": "Generative AI"
    },
    {
      "meta": "Issued Aug 2023Credential ID QNKRLV2CK94VSee credential",
      "subtitle": "Google",
      "title": "QNKRLV2CK94V"
    },
    {
      "meta": "Issued Jan 2022",
      "subtitle": "MongoDB",
      "title": "MongoDB Certified Developer, Associate (C100DEV)"
    },
    {
      "meta": "Issued May 2021Credential ID PTQ3DYLDKYQBSee credential",
      "subtitle": "DeepLearning.AI",
      "title": "Natural Language Processing with Attention Models"
    },
    {
      "meta": "Issued May 2021Credential ID 629FTVK3LHFKSee credential",
      "subtitle": "DeepLearning.AI",
      "title": "Natural Language Processing with Sequence Models"
    },
    {
      "meta": "Issued Feb 2020Credential ID EUMNKWR84Y56See credential",
      "subtitle": "IBM",
      "title": "Python for Data Science, AI & Development"
    }
  ],
  "city": "Gurugram, Haryana, India",
  "connections": 500,
  "country_code": "IN",
  "current_company": {
    "company_id": "datamagnet-co",
    "industry": "Datamagnet",
    "link": "https://www.linkedin.com/company/datamagnet-co?trk=public_profile_topcard-current-company",
    "name": "Datamagnet"
  },
  "current_company_company_id": "datamagnet-co",
  "current_company_name": "Datamagnet",
  "education": [
    {
      "description": null,
      "description_html": null,
      "end_year": "2018",
      "start_year": "2014",
      "title": "University of Petroleum and Energy Studies",
      "url": "https://in.linkedin.com/school/upesdehradun/"
    }
  ],
  "educations_details": "University of Petroleum and Energy Studies",
  "followers": 4370,
  "id": "pratik-dani",
  "input_url": "https://www.linkedin.com/in/pratik-dani",
  "linkedin_id": "pratik-dani",
  "location": "Gurugram",
  "name": "Pratik Dani",
  "people_also_viewed": [
    {
      "profile_link": "https://in.linkedin.com/in/ankit-khanna-03605421?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/anjali-pandey-933a96167?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/rashmi-nair-5258a6151?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/anant-gupta-808037230?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/bhuvek12?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/pratimarathore17?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/shubhojitsarkar?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/lakshaybhardwaj?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/viz-graffito?trk=public_profile_browsemap-profile"
    },
    {
      "profile_link": "https://in.linkedin.com/in/rohit-roy-0376a7145?trk=public_profile_browsemap-profile"
    }
  ],
  "projects": [
    {
      "description": "https://github.com/devildani/LinkedIn-Scraper",
      "start_date": "Jun 2024",
      "title": "Open Source LinkedIn Scraper"
    }
  ],
  "url": "https://www.linkedin.com/in/pratik-dani"
}
```

## Output Data Documentation

Here is the JSON fields documentation without including the sample values:

- **about** (string): A description of the person.
- **avatar** (string): The URL of the person's profile picture.
- **certifications** (list): A list of certifications associated with the person.
- **city** (string): The city in which the person is located.
- **connections** (string): The number of connections the person has.
- **country_code** (string): The country code of the person's location.
- **current_company** (dict): The person's current company.
- **current_company_company_id** (string): LinkedIn's internal and immutable ID of the person's current company.
- **current_company_name** (string): The name of the person's current company.
- **education** (list): The person's education.
- **educations_details** (string): Details about the person's education.
- **followers** (string): The number of followers the person has.
- **id** (string): LinkedIn's internal and immutable ID of this person profile.
- **input_url** (string): The URL of the person's LinkedIn profile.
- **linkedin_id** (string): The person's LinkedIn ID.
- **location** (string): The location of the person.
- **name** (string): The name of the person.
- **people_also_viewed** (list): List of people also viewed.
- **projects** (list): List of person's projects.
- **url** (string): The URL of the person's LinkedIn profile.

## Surveyyy

A Web app to create and collect survey, with data analysis admin panel.

Now it supports the following question types:

1. Slider
2. Choice (multi / single, supporting custom option)
3. Fill in the blank
4. Swiper (yes or no)

### Usage

1. access https://surveyyy.vercel.app/admin/surveys and create a new survey, including types above.
2. then we got a survey id, access https://surveyyy.vercel.app/survey/{survey_id} to fill in the survey.
   - eg. https://surveyyy.vercel.app/survey/63fb22861bca3451f4ee9262
3. share the survey to your friends, and check the result in admin panel.

### TODO

- [x] Survey Model
- [ ] Submit API
- [ ] Survey submit
- [x] Admin panel
  - [ ] Accounts && Cookie/Token
  - [x] Survey Config
    - [ ] visual
  - [ ] Data analysis

## Serverless Hosting

### mongodb

This project is based on the free mongodb provided by https://cloud.mongodb.com/v2/

### vercel deploy

The front-end is hosted on https://vercel.com/, while the serverless functions are hosted on vercel as well.

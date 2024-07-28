# Grab - Review With Your Voice

## Overview

welcome to the Grab - review with your voice project! this mobile app allows users to have a voice conversation about their meals, turning it into a review and earning rewards. the app is built to be android-first but also has an untested iphone version.

## Features

- **gamified experience**: app shows random previously-visited restaurants, refreshing every few seconds.
- **easy reviews**: users click to review the current restaurant.
- **complete feedback**: chatbot ensures reviews cover ratings, taste, portions, and pricing.
- **interactive interface**: displays restaurants and spoken ratings; bot asks probing questions for thorough reviews.

## Architecture

### Frontend

- built with mit app inventor, enabling rapid iteration and prototyping.
- designed to be mobile-first with potential production options like react native, flutter, swift (for ios), kotlin (for android), and xamarin.

### Backend

- **data storage and processing**: utilizes google cloud platform (gcp) for robust and scalable backend services.
- **real-time processing**: user interactions are processed in real-time with data stored and analyzed using gcp.
- **data integration**: integrates with google spreadsheets for easy access and further analysis.

### AI and NLP

- **language model**: uses openai gpt-4 for conversational ai and review analysis.
- **speech recognition**: google voice recognition is used for capturing and processing user voice inputs.
- **text-to-speech**: google text-to-speech provides responses to the users.
- **review parsing**: llm parses structured reviews from user’s voice inputs, extracting important keywords and details.

### Interoperability with Data Science Tools

- **data source**: app pulls customer-visited restaurant data from gcp, integrating with google spreadsheets.
- **data science tools**: compatible with multiple data science tools including:
  - google colab
  - google bigquery
  - jupyter notebooks
  - pandas (python library)
  - tableau
  - data studio
  - looker

## Future Roadmap

1. **global expansion**: support multiple languages and partner with local services.
2. **enhance ai capabilities**: improve nlp for better conversations, personalized prompts, and make the bot an intelligent agent that knows user profiles.
3. **data science integration**: use data science tools for deeper insights and predictive modeling. this is why gcp and google spreadsheets were used for seamless integration.
4. **integrate cryptocurrency rewards**: add secure cryptocurrency rewards for reviews.
5. **attract new users to the grab ecosystem**: offer grab points for bot interactions to drive exploration of grab services, even for non-users.

## Demo

check out the demo video on youtube: [https://youtu.be/m3nx4vywysw](https://youtu.be/m3nx4vywysw)

## About the Developer

- **name**: pandu sastrowardoyo
- **background**: 
  - 40-year-old female geek
  - helped make crypto legal in indonesia (cofounded asosiasi blockchain indonesia)
  - recent grad of mit no-code ai & machine learning, former expert systems dev (itb, 2008)
  - founded 3 crypto companies that raised a few million dollars:
    - debio network
    - myriad social
    - realitychain
  - won the ethdenver hackathon (2020)
  - cyberpunk / transhumanist: lifetime member of cryonics institute, welcomes agi and asi as our mind-children

## Contact

for more information, visit [https://github.com/decentricity/hackjakarta-grab-voice-reviews](https://github.com/decentricity/hackjakarta-grab-voice-reviews)

# cashbackpersonalization
AI based personalized cashback in iGraal and Shoop using RAG based targeting, and continuous eval loops
This repository contains a collection of n8n workflows used to power personalized cashback offers for two of Europe's leading cashback platforms, iGraal and Shoop.

The workflows leverage AI and business rules to dynamically adjust cashback rates at the individual user level. Personalization decisions are based on three primary inputs:

  Competitor cashback rates within each market
  Revenue performance compared to previous periods
  Profitability trends compared to previous periods

The goal is to optimize the balance between user engagement, conversion, revenue growth, and profitability by offering cashback rates that are tailored to both market conditions and business objectives.

All workflows are exported as JSON files and can be imported directly into n8n for inspection, modification, or deployment.

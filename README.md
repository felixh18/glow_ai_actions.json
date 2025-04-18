# Glow AI – Custom GPT Actions

This repository contains the action schema file for **Glow AI**, a skincare-focused GPT designed to guide users toward clean, effective, and personalized skincare solutions.

## ✨ About Glow AI

Glow AI is a supportive and simplified skincare assistant built using OpenAI’s Custom GPTs platform. It helps users:

- Get tailored skincare product recommendations
- Swap out their current products for cleaner alternatives
- Understand active ingredients in simple, clear terms

## 🧠 Actions Included

This JSON file defines 3 main actions:

1. **get_product_recommendations**  
   Recommends clean, non-toxic products based on skin type, concerns, and routine step.

2. **compare_products**  
   Takes a user-submitted product and suggests a cleaner or better-rated alternative.

3. **explain_ingredient**  
   Breaks down the purpose of an ingredient in 2–3 simple bullet points.

## 🛠 How to Use

To import these actions into the GPT builder:
1. Open your GPT in [ChatGPT Custom GPTs](https://chat.openai.com/gpts)
2. Scroll to the “Actions” section
3. Click **“Import from URL”**
4. Paste the **raw URL** of `glow_ai_actions.json`

## 🔗 Raw URL

```bash
https://raw.githubusercontent.com/felixh18/glow_ai_actions.json/main/glow_ai_actions.json

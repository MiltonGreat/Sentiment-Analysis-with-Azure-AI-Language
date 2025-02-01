# Sentiment Analysis with Azure AI Language

## Overview

This project explores the capabilities of Azure AI Language by analyzing customer reviews for hotels. Using **Language Studio**, the project demonstrates how Natural Language Processing (NLP) can extract meaningful insights from written text, such as identifying key phrases, classifying sentiment, and recognizing entities in the reviews.

The project focuses on understanding whether hotel reviews are positive, negative, or neutral while providing key insights from the review text.

## Features

- **Sentiment Analysis:** Classify reviews as positive, negative, or neutral to understand customer feedback.
- **Key Phrase Extraction:** Identify important phrases that summarize the content of the reviews.
- **Entity Recognition:** Detect mentions of known entities such as locations, people, and organizations.
- **Language Studio Integration:** Leverage Azure's no-code/low-code interface to analyze and interpret text data.

## Use Case Scenario

The fictitious travel agency **Margie’s Travel** collects customer reviews for hotel stays. Using Azure AI Language, the agency can:
- Determine the overall sentiment of reviews.
- Extract key phrases to highlight recurring feedback themes.
- Identify mentions of specific locations, amenities, or staff members.

This enables the agency to improve customer satisfaction by understanding the experiences and expectations of their customers.

## Project Workflow

1. **Create an Azure AI Language Resource:**
   - Log in to the Azure portal.
   - Navigate to "Create a resource" > "AI + Machine Learning" > "Language".
   - Select the free tier for testing purposes if available.

2. **Access Language Studio:**
   - Open [Language Studio](https://language.azure.com/).
   - Connect it to your Azure AI Language resource.

3. **Analyze Text:**
   - Upload or input sample hotel reviews.
   - Use the prebuilt sentiment analysis, key phrase extraction, or entity recognition models.

4. **Review Results:**
   - Explore the output in Language Studio to gain insights from the reviews.

## Example Analysis

![language2](https://github.com/user-attachments/assets/4a2541ec-06b6-4bb1-86f7-7212e08facab)

**Sample Review:**
"The hotel had excellent service and clean rooms, but the Wi-Fi was slow."

**Results:**
- **Sentiment:** Positive
- **Key Phrases:** `excellent service`, `clean rooms`, `slow Wi-Fi`
- **Entities:** Hotel (Location)

## Applications

This project demonstrates how Azure AI Language can be applied in real-world scenarios such as:
- **Customer Feedback Analysis:** Understand customer sentiment and identify trends in feedback.
- **Service Improvement:** Highlight areas of improvement for services or products.
- **Market Research:** Analyze text data from surveys, reviews, or social media to gain insights.

## Learnings

Through this project, I learned:
- How to use Azure AI Language Service and Language Studio for NLP tasks.
- The importance of sentiment analysis and key phrase extraction in understanding customer feedback.
- How NLP can automate and simplify the process of extracting insights from large text datasets.

## References

Exercise: [Microsoft Training Module](https://learn.microsoft.com/en-us/training/modules/analyze-text-with-text-analytics-service/4-exercise)

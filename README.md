# whatsapp_chatbot

# AI WhatsApp Automation for Local Businesses (n8n)

This is an AI-powered WhatsApp automation workflow I built using n8n for a small bookstore that was handling all customer support manually through WhatsApp.

The goal was simple: automate repetitive conversations, book searches, and order collection so the business owner could save hours every day.

## What this workflow does

• Automatically replies to customer messages on WhatsApp  
• Transcribes voice messages  
• Uses AI Vision to analyze images (e.g. payment receipts or book photos)  
• Detects customer intent (product inquiry, order, support, etc.)  
• Searches products using Hybrid Search (Vector + Full Text)  
• Sends product info back to the user  
• Collects shipping details when a customer wants to order  
• Creates a draft order and verifies payment  

## Tech Stack

• n8n  
• OpenAI  
• LangChain nodes  
• Supabase  
• WhatsApp API  

## Workflow Architecture

The system is divided into multiple subsystems:

1. **Media Processing**
   - Audio transcription
   - Image analysis

2. **Intent Classification**
   - AI classifies user intent to reduce token usage

3. **Hybrid Product Search**
   - Vector search
   - Full text search fallback

4. **Order Execution Agent**
   - Collects shipping details
   - Locks the conversation into an ordering state
   - Creates draft orders

# Download the Workflow

You can download the full workflow JSON here:

https://linktr.ee/anasmhdy

## Who is this useful for?

This automation is useful for businesses that receive a large number of WhatsApp messages such as:

• bookstores  
• ecommerce stores  
• local shops  
• service businesses  

## Want help implementing this for your business?

If you'd like a similar automation built or customized for your business, feel free to reach out.

I'm always happy to collaborate on interesting automation projects


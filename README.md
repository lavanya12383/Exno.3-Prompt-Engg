# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: 03-09-25                                                                           
### REGISTER NUMBER : 212222060019
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm: 
1. Direct Instruction Prompts

Objective: Guide the chatbot to respond concisely to customer inquiries.
Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"

2. Contextual Prompting
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.
Prompt Pattern:
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"

3. Persona-Based Prompting
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.
Prompt Pattern:
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"

4. Few-Shot Prompting
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
Prompt Pattern:
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"

5. Chain of Thought Prompting
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.
Prompt Pattern:
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"

6. Instruction with Constraints
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
Prompt Pattern:
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"

7. Reflective Prompting
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
Prompt Pattern:
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
Output: AI-Powered Customer Support Chatbot – Conversation Flow
Step 1: Greeting (Straightforward Prompt)

Bot: “Hi 👋 I’m your virtual assistant. Do you need help with order tracking, product troubleshooting, or general inquiries?”
User: “Order tracking.”

Step 2: Tabular Format Prompting

Bot: “Great! Here are the services I can provide for your order ”

Option	Service	Example Question
1️⃣	Track current status	“Where is my package?”
2️⃣	Delivery issues	“Why is my order delayed?”
3️⃣	Modify or cancel order	“Can I change my address?”

Bot: “Please choose 1, 2, or 3.”
User: “1.”

Step 3: Missing Word Prompting

Bot: “To track your package, I’ll need your ______.”
User: “Order ID.”
Bot: “Thank you! Please type your order ID.”
User: “12345ABC.”

Step 4: Order Status Response

Bot: “✅ Order 12345ABC is currently out for delivery and should arrive by tomorrow evening.”

Step 5: Preceding Question Prompting (Optional Follow-up)

Bot: “Earlier, you chose order tracking. Do you also want to check if you’re eligible for real-time SMS updates?”
User: “Yes.”
Bot: “Perfect! I’ve activated SMS notifications for your order. ”

#Summary of Techniques Used

Straightforward Prompt → Asked user to choose category (Step 1).

Tabular Format Prompting → Displayed options in a table (Step 2).

Missing Word Prompting → User filled in “Order ID” (Step 3).

Preceding Question Prompting → Referred to earlier choice for follow-up (Step 5). The various types of Prompts are executed successfully.




# Output: Thus the Prompts were exected succcessfully .


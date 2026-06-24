# CHATBOT-WITH-RULE-BASEDRESPONSES
Build a simple chatbot that responds to user inputs based onpredefined rules. Use if-else statements or pattern matchingtechniques to identify user queries and provide appropriateresponses. This will give you a basic understanding of naturallanguage processing and conversation flow.
# def chatbot():
    print("🤖 ChatBot: Hello! Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        if user_input in ["hello", "hi", "hey"]:
            print("🤖 ChatBot: Hello! How can I help you today?")

        elif "how are you" in user_input:
            print("🤖 ChatBot: I'm doing great! Thanks for asking.")

        elif "your name" in user_input:
            print("🤖 ChatBot: I am a Rule-Based ChatBot.")

        elif "help" in user_input:
            print("🤖 ChatBot: I can answer simple questions like greetings, my name, and basic help.")

        elif "time" in user_input:
            from datetime import datetime
            current_time = datetime.now().strftime("%H:%M:%S")
            print(f"🤖 ChatBot: The current time is {current_time}")

        elif user_input == "bye":
            print("🤖 ChatBot: Goodbye! Have a nice day!")
            break

        else:
            print("🤖 ChatBot: Sorry, I don't understand that.")
# Run the chatbot
chatbot()
# Sample Conversation
🤖 ChatBot: Hello! Type 'bye' to exit.

You: hi
🤖 ChatBot: Hello! How can I help you today?

You: what is your name
🤖 ChatBot: I am a Rule-Based ChatBot.

You: how are you
🤖 ChatBot: I'm doing great! Thanks for asking.

You: bye
🤖 ChatBot: Goodbye! Have a nice day!How It Works
# Takes user input using input().
# Converts input to lowercase for easier matching.
# Uses if-elif-else conditions to identify keywords or phrases.
# Returns predefined responses.
# Continues the conversation until the user types "bye".
This approach is the foundation of simple conversational agents and helps in understanding basic Natural Language Processing (NLP) concepts such as pattern matching and conversation flow.

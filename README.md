
print("🤖 AI App Developer Bot")
print("I can help you with app development!")
print("Type 'help' for commands.")
print("Type 'bye' to exit.")

while True:
    user = input("\nYou: ").lower().strip()

    if user == "hi" or user == "hello":
        print("Bot: Hello! 👋 I am your AI App Developer.")

    elif "who are you" in user:
        print("Bot: I am an AI App Developer Assistant.")
        print("Bot: I can help with app ideas, features, UI and coding.")

    elif "app idea" in user:
        print("Bot: Here are some ideas:")
        print("1. AI Chatbot")
        print("2. Medicine Finder")
        print("3. Student Helper")
        print("4. AI Study Assistant")

    elif "ui" in user or "design" in user:
        print("Bot: For a good UI, use simple buttons,")
        print("clear text, suitable colors and easy navigation.")

    elif "python" in user:
        print("Bot: Python is useful for AI, automation and backend development.")

    elif "android" in user:
        print("Bot: For Android apps, you can learn Kotlin, Java or Flutter.")

    elif "feature" in user:
        print("Bot: Common app features include:")
        print("- Login")
        print("- Search")
        print("- Notifications")
        print("- User profile")
        print("- Database")

    elif user == "help":
        print("Bot: Try asking:")
        print("- hi")
        print("- give me an app idea")
        print("- help with UI")
        print("- tell me about Python")
        print("- Android development")
        print("- features")
        print("- bye")

    elif user == "bye":
        print("Bot: Goodbye! Keep building! 🚀")
        break

    else:
        print("Bot: I don't understand yet.")
        print("Bot: Type 'help' to see what I can do.")

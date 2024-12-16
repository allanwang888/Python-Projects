# Simple Chatbot AI using Python

# Define responses
responses = {
    "hello": "Hi there! How can I help you?",
    "how are you": "I'm just a bunch of code, but I'm doing great! How about you?",
    "what is your name": "I am ChatBot, your virtual assistant!",
    "bye": "Goodbye! Have a great day!",
    "default": "I'm sorry, I don't understand that. Can you try rephrasing?"
}

# Function to get response
def get_response(user_input):
    # Make input lowercase for easier matching
    user_input = user_input.lower()

    # Check for a matching keyword
    for key in responses:
        if key in user_input:
            return responses[key]
    
    # Default response if no match is found
    return responses["default"]

# Main program loop
def chatbot():
    print("ChatBot: Hello! Type 'bye' to exit.")
    while True:
        user_input = input("You: ")  # Get user input
        if user_input.lower() == "bye":
            print("ChatBot:", responses["bye"])
            break
        response = get_response(user_input)
        print("ChatBot:", response)

# Run the chatbot
if __name__ == "__main__":
    chatbot()

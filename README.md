# decision_making_bot
def decision_making_bot():
    print("Welcome to the Basic Decision-Making Bot!")
    print("I will help you make a simple decision based on your input.")
    while True:
        print("\nLet's get started!")
        print("1: Ask for advice on daily activities.")
        print("2: Make a decision based on a yes/no question.")
        print("3: Exit")
def daily_activity_advice():
    print("\nI can help you choose what to do!")

    # Ask the user questions to give daily advice
    weather = input("Is it sunny or rainy today? (sunny/rainy): ").lower()
    time_of_day = input("Is it morning, afternoon, or evening? (morning/afternoon/evening): ").lower()

    if weather == 'sunny':
        if time_of_day == 'morning':
            print("It's a great time for a morning walk!")
        elif time_of_day == 'afternoon':
            print("Why not visit a park or go for a bike ride?")
        else:
            print("A beautiful evening for a relaxing stroll.")
    elif weather == 'rainy':
        if time_of_day == 'morning':
            print("How about reading a book or having a cozy breakfast inside?")
        elif time_of_day == 'afternoon':
            print("Maybe it's a good time to catch up on some indoor hobbies.")
        else:
            print("A perfect evening to watch a movie or listen to some calming music.")
    else:
        print("I'm not sure about that weather! But staying flexible and relaxed is always a good option.")
 def yes_no_decision():
    """

    """
    print("\nLet's help you decide with a simple yes/no question.")

    # User asks a yes/no question
    question = input("Ask your yes/no question: ")

    # Simple decision-making logic based on length of the question
    if len(question) % 2 == 0:
        print("My answer is: Yes!")
    else:
        print("My answer is: No!")

    print("Remember, the decision is yours! This is just a fun way to help you think about it.")

if __name__ == "__main__":
    decision_making_bot()       

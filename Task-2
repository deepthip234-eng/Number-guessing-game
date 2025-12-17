def task_guessing_game():
    """
    Task: Number Guessing Game
    Topics: Random, While True, Input, Break, If/Else
    """
    print("\n--- FINAL TASK: Number Guessing Game ---")
    
    # 1. Setup: Computer picks a number between 1 and 20
    secret_number = random.randint(1, 20)
    attempts = 0
    
    print("I am thinking of a number between 1 and 20.")

    # 2. Infinite Loop: We don't know how many guesses the user needs
    while True:
        try:
            user_input = input("Your guess: ")
            guess = int(user_input)
            attempts = attempts + 1
            
            # 3. Logic: Compare guess to secret
            if guess < secret_number:
                print("Higher! ⬆️")
            elif guess > secret_number:
                print("Lower! ⬇️")
            else:
                # 4. Win Condition
                print(f"🎉 You Win! The number was {secret_number}.")
                print(f"It took you {attempts} guesses.")
                break # 5. Exit the loop
                
        except ValueError:
            print("Please enter a valid numbe:")

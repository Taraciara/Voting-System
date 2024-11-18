# voting_system.py

options = {"Option A": 0, "Option B": 0, "Option C": 0}

def cast_vote(option):
    if option in options:
        options[option] += 1
    else:
        print("Invalid option.")

def show_results():
    print("Voting Results:")
    for option, votes in options.items():
        print(f"{option}: {votes} votes")

# Sample usage
cast_vote("Option A")
cast_vote("Option B")
cast_vote("Option A")
show_results()

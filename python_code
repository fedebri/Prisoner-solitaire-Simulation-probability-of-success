import random
carte = [1,2,3,4,5,6,7,8,9,10,\
         1,2,3,4,5,6,7,8,9,10,\
         1,2,3,4,5,6,7,8,9,10,\
         1,2,3,4,5,6,7,8,9,10]

def prisonerSolitaire(deck):
    
    random.shuffle(deck)
    for i in range(0, len(deck), 3):
        
        if deck[i] == 1: 
                results['X'] += 1
                break
        try:
            if deck[i+1] == 2:
                results['X'] += 1
                break
            if deck[i+2] == 3:
                results['X'] += 1
                break

        except IndexError:
            results['O'] += 1

def simGames(deck, numTrials):
    results = {'O' : 0 , 'X' : 0}
    for i in range (numTrials):
        prisonerSolitaire(deck)

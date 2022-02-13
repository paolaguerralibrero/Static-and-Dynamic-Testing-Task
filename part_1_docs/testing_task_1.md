### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1:    # double equals == are needed
      return True
    else        # missing colon after else, should read "else:"
      return False
   

  dif highest_card(self, card1 card2): # there is a typo in "def", there is missing comma after "card1"
  if card1.value > card2.value: #missing 1 extra indentation
    return card      # this should be card1, #missing 2 extra indentations
  else:           #missing 1 extra indentation
    return card2   #missing 2 extra indentations
  


def cards_total(self, cards): #missing indentation, needs to be at the same level of other functions
  total  #missing to finish the variable
  for card in cards:
    total += card.value
    return "You have a total of" + total   # missing round brackets ("You have a total of" + total) and total needs to be converted to a string.
  
```

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
#   We need to use == instead of =
    if card.value = 1:
      return True
#   a ':' is missing in the line below
    else
      return False
   

# 'dif' should be 'def' and there should be a comma between card1 and card2
  dif highest_card(self, card1 card2):
#   missing indentatiomn below
  if card1.value > card2.value:
#   it should return card1 and not 'card' in the line below
    return card
  else:
    return card2
  

# below lines need to be indented properly
def cards_total(self, cards):
# = 0 should be at the end of the line below
  total
  for card in cards:
    total += card.value
# we need to convert the line below to a string and move it outside of the for loop
    return "You have a total of" + total
  
```
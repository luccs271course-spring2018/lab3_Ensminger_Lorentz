# Ensminger Lorentz Lab 3
## These are the Answers

##From TestList
1.also try with a LinkedList - does it make any difference?
2.list.remove(5); // what does this method do?
        This removes the item at the 5th index of the list. It does not matter
        what the value of the integer at that index is.
3.list.remove(Integer.valueOf(5)); // what does this one do?
        This removes the first instance of the integer 5 in the list. The method
        interates through the list and the first time it hits the indicated
        value, it removes that value.

## From TestList
1. also try with a LinkedList - does it make any difference?
        The difference comes in how the two types of list operate. The array list 
        works as a list that you just move down without objects in the list
        point to those before or after them. Linked list operate with nodes that 
        point those infront and after themselves. For instance, when you remove 
        an item from a array list that item simply slips out of the order and the 
        process of moving through the list continues. When removing an item from
        a linked list, the item before the one removed is now made to point to the
        one after the specified item and the item after the one removed points to
        the one before it. On the small scale the array list runs faster and is 
        more efficient, but on the larger scale, a linked list is more effiecient.
2. list.remove(5); // what does this method do?
        This removes the item at the 5th index of the list. It does not matter
        what the value of the integer at that index is.
3. list.remove(Integer.valueOf(5)); // what does this one do?
        This removes the first instance of the integer 5 in the list. The method
        interates through the list and the first time it hits the indicated
        value, it removes that value.

## From TestIterator
1. TODO also try with a linkedlist?
    Once importing java.util.* linked list does not appear to do anything function wise to the code

2. What happens if you use list.remove(77)?
        It throws a IndexOutofBounds exceptions

[Data visualization](https://docs.google.com/spreadsheets/d/1dckLVJAO3MqpKccG0OPcwPAtMZBF-q_hb77dONblKyM/edit?usp=sharing)

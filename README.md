# Create an Double Ended Queue using Javafx Application
Dequeue: A double-ended queue or deque (pronounced “deck”) is a generalization of a stack and a queue that supports adding and removing items from either the front or the back of the data structure. 
Create a generic data type Deque that implements the following API:

public class Deque <Item> implements Iterable <Item> {

// construct an empty deque

public Deque()

// is the deque empty?

public boolean isEmpty()

// return the number of items on the deque

public int size()

// add the item to the front

public void addFirst(Item item)

// add the item to the back

public void addLast(Item item)

// remove and return the item from the front

public Item removeFirst()

// remove and return the item from the back

public Item removeLast()

// return an iterator over items in order from front to back

public Iterator <Item> iterator()

// unit testing (required)

public static void main(String[] args)

}

Corner cases:

Throw the specified exception for the following corner cases:
1) Throw an IllegalArgumentException if the client calls either addFirst() or addLast() with a null argument.
2) Throw a java.util.NoSuchElementException if the client calls either removeFirst() or removeLast when the deque is empty.
3) Throw a java.util.NoSuchElementException if the client calls the next() method in the iterator when there are no more items to return.

Java Data Structures
This project includes implementations of various data structures in Java.

MyLinkedList
The MyLinkedList class implements a singly linked list. It implements the List interface, and provides methods for adding, removing, and accessing elements in the list.

MyArrayList
The MyArrayList class implements an array-based list. It implements the List interface, and provides methods for adding, removing, and accessing elements in the list. If the size of the array is not large enough to accommodate a new element, the implementation creates a new array with double the size of the original array.

MyLinkedListStack
The MyLinkedListStack class is a stack implementation using MyLinkedList. It provides the standard stack operations, including push, pop, peek, isEmpty, and size.

MyArrayListStack
The MyArrayListStack class is a stack implementation using MyArrayList. It provides the standard stack operations, including push, pop, peek, isEmpty, and size.

MyLinkedListQueue
The MyLinkedListQueue class is a queue implementation using MyLinkedList. It provides the standard queue operations, including enqueue, dequeue, peek, isEmpty, and size.

MyArrayListQueue
The MyArrayListQueue class is a queue implementation using MyArrayList. It provides the standard queue operations, including enqueue, dequeue, peek, isEmpty, and size.

Getting Started
Prerequisites
To use these data structures, you need to have Java 8 or later installed on your system.

Installation
You can download the source code for each data structure implementation, compile the code using a Java compiler, and then use the compiled classes in your own Java projects.

import java.util.ArrayList;
import java.util.LinkedList;

public class Main {
    public static void main(String[] args) {
            MyArrayListStack<Integer> array = new MyArrayListStack<>();
            array.push(1);
            array.push(2);
            array.push(3);
            array.push(4);
            array.push(5);
            array.push(7);
        System.out.println(array.size());
        System.out.println(array.isEmpty());
        MyArrayListQueue<Integer> arrayListQueue = new MyArrayListQueue<>();
        arrayListQueue.enqueue(1);
        arrayListQueue.enqueue(2);
        arrayListQueue.enqueue(3);

        MyLinkedListQueue<Integer> myLinkedListQueue = new MyLinkedListQueue<>();
        myLinkedListQueue.enqueue(2);
        myLinkedListQueue.enqueue(3);
        myLinkedListQueue.enqueue(5);
        myLinkedListQueue.enqueue(6);
        myLinkedListQueue.enqueue(7);
    }
}

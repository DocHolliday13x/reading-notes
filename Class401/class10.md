# Class 10 Reading: Stacks & Queues

## Resources

- [Stacks and Queues](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)

## Stacks and Queues

- To turn in your reading, “Reply” to the discussion by teaching something that you learned. Then review what one of your classmates learned, and leave a comment.

- Some ideas for how you might want to teach:

  - Use an analogy
  - Explain a detail in depth
  - Use WHY, WHAT, HOW structure
  - Tutorial / walk through an example
  - Write a quiz
  - Create a vocabulary/definition list
  - Write a cheat sheet
  - Create a diagram / visualization / cartoon of a topic
  - Anthropomorphize the concepts, and write a conversation between them
  - Build a map of the information
  - Construct a fill-in-the-blank worksheet for the topic

## Stacks And Queues Cheat Sheet

### Stacks

- A stack is a data structure that consists of `Nodes`. Each `Node` references the next `Node` in the stack, but does not reference its previous.

- Common terminology for a stack is

  - `Push` - Nodes or items that are put into the stack are pushed

  - `Pop` - Nodes or items that are removed from the stack are popped. When you attempt to pop an empty stack an exception will be raised.

  - `Top` - This is the top of the stack.

  - `Peek` - When you `Peek` you will view the value of the `Top` Node in the stack. When you attempt to `Peek` an empty stack an exception will be raised.

  - `IsEmpty` - returns true when stack is empty otherwise returns false.

- Stacks follow these concepts:
  
  - FILO
  
    - (First In Last Out) Means that the first item added in the stack will be the last item popped out of the stack.
  
  - LIFO
  
    - (Last In First Out) Means that the last item added to the stack will be the first item popped out of the stack.

- Push O(1)

  - Pushing a Node onto a stack will always be an `O(1)` operation. This is because it takes the same amount of time no matter how many Nodes (n) you have in the stack.

- Pop O(1)

  - Popping a Node off a stack is the action of removing a Node from the `Top`. When conducting a `pop`, the `Top` Node will be re-assigned to the Node that lives below and the `Top` Node is returned to the user.

  - Typically, you would check `isEmpty` before conducting a `pop`.

- Peek O(1)

  - When conducting a `peek`, you will only be inspecting the `Top` Node of the stack.

  - Typically, you would check `isEmpty` before conducting a `peek`.

- IsEmpty O(1)

  - Here is the pseudocode for `isEmpty`

    ```JavaScript
    ALGORITHM isEmpty()
        // INPUT <-- none
        // OUTPUT <-- boolean
        return top = NULL
    ```

### Queues

- A queue is a linear structure which follows a particular order in which the operations are performed. The order is `First In First Out` (FIFO).

- A good example of a queue is any queue of consumers for a resource where the consumer that came first is served first.

- Common terminology for a queue is

  - `Enqueue` - Nodes or items that are added to the queue.

  - `Dequeue` - Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.

  - `Front` - This is the front/first Node of the queue.

  - `Rear` - This is the rear/last Node of the queue.

  - `Peek` - When you `Peek` you will view the value of the `front` Node in the queue. If called when the queue is empty an exception will be raised.

  - `IsEmpty` - returns true when queue is empty otherwise returns false.

- Queues follow these concepts:

  - FIFO

    - (First In First Out) This means that the first item in the queue will be the first item out of the queue.

  - LILO

    - (Last In Last Out) This means that the last item in the queue will be the last item out of the queue.

- Enqueue O(1)

  - When you add an item to a queue, you use the `enqueue` action. This is done with an `O(1)` operation.

- Dequeue O(1)

  - When you remove an item from a queue, you use the `dequeue` action. This is done with an `O(1)` operation.

- Peek O(1)

  - When conducting a `peek`, you will only be inspecting the `Front` Node of the queue.

  - Typically, you would check `isEmpty` before conducting a `peek`.

- IsEmpty O(1)

  - Here is the pseudocode for `isEmpty`

    ```JavaScript
    ALGORITHM isEmpty()
        // INPUT <-- none
        // OUTPUT <-- boolean
        return front = NULL
    ```

- ![Stacks GIF](https://media.giphy.com/media/10aADbYxnJlc9q/giphy.gif)

- and

- ![Queues GIF](https://media.giphy.com/media/5YuhLwDgrgtRVwI7OY/giphy.gif)

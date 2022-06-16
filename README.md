# ringmap
An mmap backed ring of arbitrary sized data.

  - freelist: A simple free list implementation.
  - gapstore: Store variable sized []byte in a fragmented fixed size []byte.
  - index: An index implemented as ring.
  - delayqueue: A storage backed queue that reprodues elements after a defined delay.

`import "github.com/JonathanLogan/delayqueue"`
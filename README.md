# Project Reflection

### What was the problem you were solving in the projects for this course?
I developed a Course Management System for ABCU that required implementing three different data structures (Vector, Hash Table, and Binary Search Tree) to manage course information. The system needed to:
1. Load course data from files
2. Display an alphanumerically sorted list of courses
3. Search and display specific course information including prerequisites
4. Validate prerequisites during data loading

### How did you approach the problem? Consider why data structures are important to understand.
I approached this problem by implementing and analyzing three distinct data structures:

1. **Vector Implementation**
   - Simple, continuous memory structure
   - O(n²) loading time due to prerequisite validation
   - O(n log n) sorting complexity
   - O(n) search time

2. **Hash Table Implementation**
   - O(1) average lookup time
   - O(n) loading time
   - Required additional work for sorted output
   - Excellent for individual queries

3. **Binary Search Tree Implementation**
   - O(log n) search time
   - Natural ordering maintenance
   - O(n log n) loading time
   - Balanced functionality and performance

Understanding data structures was crucial because each implementation offered different trade-offs between performance, memory usage, and complexity. This knowledge allowed me to make an informed decision based on the specific requirements.

### How did you overcome any roadblocks you encountered while going through the activities or project?
Key challenges I addressed included:
- Implementing prerequisite validation across all three data structures
- Managing the two-pass file reading process for prerequisite verification
- Balancing performance requirements with functionality
- Handling the complexity of maintaining sorted output in different data structures
- Implementing proper error handling and input validation

### How has your work on this project expanded your approach to designing software and developing programs?
This project enhanced my approach by:
- Teaching me to analyze runtime complexities (O(n), O(log n), etc.)
- Demonstrating how different data structures can solve the same problem with different trade-offs
- Showing the importance of choosing the right data structure based on specific requirements
- Understanding the relationship between memory usage and performance

### How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?
The project improved my programming practices through:
- Creating clear pseudocode before implementation
- Implementing consistent error handling across different data structures
- Understanding the importance of modular design
- Learning to balance performance with code maintainability
- Developing a systematic approach to analyzing and comparing different implementations

Based on the analysis, I ultimately recommended the Binary Search Tree implementation as it provided the best balance of:
- Natural ordering for sorted output
- Efficient O(log n) searches
- Reasonable memory usage
- Scalable performance for larger datasets
- Good balance between functionality and implementation complexity

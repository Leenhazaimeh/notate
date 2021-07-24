# Pain vs. Suffering
It is important to prepare ourselves mentally for the pain we’re expected to experience in the coming 10-week spectacular learning journey. A good thing to keep in mind is that the pain won’t be aimless, it won’t be suffering. It’ll be pain in favor of growth.

Big O notation


Big O notation is:


1. used in Computer Science to describe the performance or complexity of an algorithm.

2. describes the worst-case scenario, and can be used to describe the execution time required or the space used (e.g. in memory or on disk) by an algorithm.

## Common Orders of Growth:
O(1)

describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

**example:**


bool IsFirstElementNull(IList elements) {return elements[0] == null;}

O(N)

An algorithm with linear behaviour and is directly proprtional with the input data set size.





*Example(showing how this order favours the worst-case performance scenario):*



bool ContainsValue(IEnumerable string> elements, string value) { foreach (var element in elements) { if (element == value) return true; }
return false; }

O(N²)

An algorithm that is directly proprtional with the square of the input data set size.
common among algorithms with nested iterations over the data set.
Example:
bool ContainsDuplicates(IList elements) { for (var outer = 0; outer < elements.Count; outer++) { for (var inner = 0; inner < elements.Count; inner++) { // Don't compare with self if (outer == inner) continue;

      if (elements[outer] == elements[inner]) return true; 
  }
}
return false; }

O(2^N)

an algorithm whose growth doubles with each addition to the input data set.

The growth curve of an O(2^N) function is exponential — starting off very shallow, then rising meteorically.

Example:
recursive calculation of Fibonacci numbers
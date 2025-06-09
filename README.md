## 📘 Java LeetCode Study Guide: Must-Know Methods by Data Structure & Type

### 🔧 General Utility
| Method | Description |
|--------|-------------|
| `Math.max(a, b)` | Returns the greater of two values |
| `Math.min(a, b)` | Returns the smaller of two values |
| `Math.abs(x)` | Absolute value of x |
| `Math.pow(x, y)` | x raised to the power y |
| `Math.sqrt(x)` | Square root of x |
| `Math.floor(x)` | Rounds down to nearest int |
| `Math.ceil(x)` | Rounds up to nearest int |
| `Math.random()` | Returns a random double between 0.0 and 1.0 |
| `Arrays.sort(arr)` | Sorts the array in ascending order |
| `Collections.sort(list)` | Sorts a list in ascending order |
| `Collections.reverse(list)` | Reverses the list order |
| `Collections.max(list)` | Finds the max element in a list |
| `Collections.min(list)` | Finds the min element in a list |

---

### 🔢 Arrays
| Method | Description |
|--------|-------------|
| `Arrays.toString(arr)` | Returns string representation of array |
| `Arrays.copyOf(arr, len)` | Copies first `len` elements |
| `Arrays.equals(arr1, arr2)` | Checks if two arrays are equal |
| `Arrays.fill(arr, val)` | Fills array with val |
| `Arrays.binarySearch(arr, key)` | Searches sorted array for key (returns index or -1) |
| `Arrays.stream(arr)` | Turns array into Stream for further ops |

---

### 📋 ArrayList
| Method | Description |
|--------|-------------|
| `list.add(val)` | Adds element to list |
| `list.add(index, val)` | Adds element at index |
| `list.get(index)` | Returns element at index |
| `list.set(index, val)` | Replaces element at index |
| `list.remove(index/obj)` | Removes by index or object |
| `list.contains(obj)` | Checks if value exists in list |
| `list.size()` | Returns number of elements |
| `list.isEmpty()` | Checks if list is empty |
| `list.clear()` | Removes all elements |
| `list.indexOf(obj)` | Returns first index of object |
| `Collections.sort(list)` | Sorts list in place |

---

### 📦 HashMap
| Method | Description |
|--------|-------------|
| `map.put(key, val)` | Adds or updates a key-value pair |
| `map.get(key)` | Returns value for key or null |
| `map.containsKey(key)` | Checks if key exists |
| `map.containsValue(val)` | Checks if value exists |
| `map.remove(key)` | Removes key-value pair |
| `map.size()` | Returns number of entries |
| `map.isEmpty()` | Checks if map is empty |
| `map.keySet()` | Returns set of all keys |
| `map.values()` | Returns collection of values |
| `map.entrySet()` | Returns set of key-value pairs |
| `map.put(key, map.getOrDefault(key, 0) + 1)' | Returns current count or 0 if not present and increments by 1 |

---

### 🔢 HashSet
| Method | Description |
|--------|-------------|
| `set.add(val)` | Adds element to set |
| `set.contains(val)` | Checks if element is in set |
| `set.remove(val)` | Removes element from set |
| `set.size()` | Returns number of elements |
| `set.isEmpty()` | Checks if set is empty |
| `set.clear()` | Clears the set |

---

### 📚 String
| Method | Description |
|--------|-------------|
| `s.length()` | Length of string |
| `s.charAt(i)` | Returns character at index i |
| `s.substring(start, end)` | Substring from start to end-1 |
| `s.indexOf(sub)` | First index of substring or -1 |
| `s.lastIndexOf(sub)` | Last index of substring or -1 |
| `s.startsWith(prefix)` | Checks if string starts with prefix |
| `s.endsWith(suffix)` | Checks if string ends with suffix |
| `s.equals(str)` | Compares string values |
| `s.equalsIgnoreCase(str)` | Case-insensitive comparison |
| `s.contains(sub)` | Checks if substring exists |
| `s.replace(a, b)` | Replaces all a's with b's |
| `s.split(" ")` | Splits string by space or regex |
| `s.trim()` | Removes leading and trailing whitespace |
| `String.valueOf(x)` | Converts x to string |
| `String.join(delimiter, list)` | Joins strings with delimiter |
| `s.toCharArray()` | Converts string to char array |
| `s.toLowerCase()` | Converts to lowercase |
| `s.toUpperCase()` | Converts to uppercase |
| `s.isEmpty()` | Checks if string is empty |

---

### 🧐 Character
| Method | Description |
|--------|-------------|
| `Character.isLetter(c)` | Checks if char is a letter |
| `Character.isDigit(c)` | Checks if char is a digit |
| `Character.isLowerCase(c)` | Checks if char is lowercase |
| `Character.isUpperCase(c)` | Checks if char is uppercase |
| `Character.toLowerCase(c)` | Converts to lowercase |
| `Character.toUpperCase(c)` | Converts to uppercase |

---

### 🔢 Integer / int
| Method | Description |
|--------|-------------|
| `Integer.parseInt(str)` | Converts string to primitive int |
| `Integer.parseInt(binaryStr, 2)` | Converts binary string (e.g. "101") to decimal int |
| `Integer.toString(i)` | Converts int to string |
| `Integer.toBinaryString(i)` | Converts int to binary string (e.g. 5 → "101") |
| `Integer.valueOf(str)` | Converts string to Integer object |
| `Integer.max(a, b)` | Returns larger of two ints |
| `Integer.min(a, b)` | Returns smaller of two ints |
| `Integer.compare(a, b)` | Compares two ints |
| `Integer.bitCount(i)` | Number of 1s in binary form of i |


---

### 🔢 Double / double
| Method | Description |
|--------|-------------|
| `Double.parseDouble(str)` | Converts string to double |
| `Double.toString(d)` | Converts double to string |
| `Double.isNaN(d)` | Checks if value is NaN |
| `Double.isInfinite(d)` | Checks if value is infinite |
| `Double.compare(a, b)` | Compares two doubles |

---

### 🔘 Boolean / boolean
| Method | Description |
|--------|-------------|
| `Boolean.parseBoolean(str)` | Converts string to boolean |
| `Boolean.toString(b)` | Converts boolean to string |
| `Boolean.logicalAnd(a, b)` | Logical AND |
| `Boolean.logicalOr(a, b)` | Logical OR |
| `Boolean.logicalXor(a, b)` | Logical XOR |

---

### 📤 Queue (LinkedList)
| Method | Description |
|--------|-------------|
| `queue.add(val)` | Adds to the queue (throws on fail) |
| `queue.offer(val)` | Adds to the queue (returns false on fail) |
| `queue.poll()` | Retrieves and removes head or null |
| `queue.remove()` | Retrieves and removes head or throws exception |
| `queue.peek()` | Returns head without removing or null |
| `queue.element()` | Returns head without removing or throws exception |

---

### 📥 Stack (via Deque or Stack class)
| Method | Description |
|--------|-------------|
| `stack.push(val)` | Pushes element onto stack |
| `stack.pop()` | Removes and returns top element |
| `stack.peek()` | Returns top element without removing |
| `stack.isEmpty()` | Checks if stack is empty |

---

### 🔁 PriorityQueue (Min-Heap by default)
| Method | Description |
|--------|-------------|
| `pq.add(val)` | Adds to queue |
| `pq.poll()` | Removes and returns smallest element |
| `pq.peek()` | Returns smallest without removing |
---

### 🔄 Type Conversion Methods

| From → To | Method |
|-----------|--------|
| `int` → `String` | `Integer.toString(i)` or `String.valueOf(i)` |
| `String` → `int` | `Integer.parseInt(s)` or `Integer.valueOf(s)` |
| `double` → `String` | `Double.toString(d)` or `String.valueOf(d)` |
| `String` → `double` | `Double.parseDouble(s)` |
| `boolean` → `String` | `Boolean.toString(b)` or `String.valueOf(b)` |
| `String` → `boolean` | `Boolean.parseBoolean(s)` |
| `char` → `String` | `Character.toString(c)` or `String.valueOf(c)` |
| `String` → `char` | `s.charAt(0)` (first character only) |
| `int` → `char` | `(char) i` (casts ASCII value to character) |
| `char` → `int` | `(int) c` (gets ASCII value) |
| `double` → `int` | `(int) d` (explicit cast, truncates decimal) |
| `int` → `double` | `double d = i;` (implicit widening conversion) |


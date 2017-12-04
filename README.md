# Software Studio Assignment 3 - Basic Collections

We've implemented a simple data structure framework. 

There are some uncompleted functions. Please finish them.

## Requirements

1. Modify the `LinkedList` class so that it implements `Deque` interface.

2. Finish the `resize()` method in `HashMap` class.

## Hints

- Make sure you understand how `header` works in the following methods of `LinkedList`:
	- `add`
	- `get`
	- `remove`

- In `resize()` of `HashMap`, you may create a new table and rehash all old entries to this new table one-by-one.

## Submission

The procedure of submission is as following:

1. Fork our [template repository][1] on GitLab.
2. Change the **"Visibility Level"** of the forked repository to **private**.
3. Clone the repository you forked.
4. Finish your work, run test cases to check if your implementation meets the requirements.
5. Commit your work, push to GitLab and then open a merge request to submit.

Note:

- Don't forget to add files to index before commiting.
- To submit a newer version after opening a merge request, simply push again.

Please refer to the lab slides: [Version Control & Debugger][2] for a complete tutorial.



[1]: http://shwu10.cs.nthu.edu.tw/2016-software-studio/assignment-3-basic-collections
[2]: http://shwu10.cs.nthu.edu.tw/2016-software-studio/release-slides/raw/master/03_Lab_VCS_Debugger-copy-2.pdf

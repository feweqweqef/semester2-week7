@feweqweqef ➜ /workspaces/semester2-week7/session1/task1 (main) $ python crash.py
Traceback (most recent call last):
  File "/workspaces/semester2-week7/session1/task1/crash.py", line 9, in <module>
    assign_values(data)
  File "/workspaces/semester2-week7/session1/task1/crash.py", line 5, in assign_values
    x[i] = (i + 1) * (i + 1);
    ~^^^
IndexError: list assignment index out of range


@feweqweqef ➜ /workspaces/semester2-week7/session1/task1 (main) $ ./a.out
Done!
*** stack smashing detected ***: terminated
Aborted (core dumped)
``python3-dane`` was a library which was supposed to help with implementing
DANE support in python applications.

Unfortunately, this library was based on the (at that time) latest DANE RFC and
did not know about certain clarifications and operational concerns which were
drafted at that time.

These clarifications make it unreasonable to implement DANE by bolting it on
top of an existing SSL stack and pretty much requires to implement DANE right
in the SSL library, which is out of scope for this project.

Thank you for the interest.

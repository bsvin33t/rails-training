*Vineeth's Rails Training*
Mainly using Rauils by Example Book

For me:
	To start spork, do
	$ bundle exec guard

	starting the test environment. Here is the sequence I recommend:

1. Start Spork in a terminal window.
2. Write a single test or small group of tests.
3. Run Command-Shift-R to verify that the test or test group is red.
4. Write the corresponding application code.
5. Run Command-Shift-E to run the same test/group again, verifying that it’s green.
6. Repeat steps 2–5 as necessary.
7. When reaching a natural stopping point (such as before a commit), run rspec spec/ at the command line to confirm that the entire test suite is still green.
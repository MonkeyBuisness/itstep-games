all: run

run:
	make rm
	javac ./srv/*.java ./game/*.java ./example/*.java -Xdiags:verbose
	java srv.Main
	make rm

rm:
	rm -f ./example/*.class
	rm -f ./game/*.class
	rm -f ./srv/*.class
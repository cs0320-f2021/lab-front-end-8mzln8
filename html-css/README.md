# README
To run use in command line use:
`./run --data=<list of files> [--prefix] [--whitespace] [--led=<led>]`
where list of files is a string with each file path separated by commas and no spaces.

This will give you a barebones REPL, where you can enter text and you will be output at most 5 suggestions sorted alphabetically.

To run the GUI from command line add the following flags to the above:
`./run --gui [--port=<port>]`


A bunch of random commands to save myself the trouble:
./run -data=<"src/main/resources/spark/template/freemarker/main.ftl"> \n --gui
./run -data=<"src/main/resources/spark/template/freemarker/autocorrect.ftl"> \n --gui


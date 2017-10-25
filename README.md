# boofuzz-http
Simple HTTP fuzzer example for boofuzz.

This is NOT a thorough HTTP fuzz test. If you would like to contribute to improvements, please open a pull request!

## Getting started

### Install boofuzz

    pip install boofuzz

### Run an HTTP server
Any server. Obscure open source projects are a nice place to look for bugs.

Since we're trying to break the program anyway, you may want to run it in a
Virtual Machine.

You can also likely scan your network and find some open port 80s or port 443s. Of course this testing method can
cause harm so beware what you test against.

### Run the fuzzer

    python http.py

It's fun to watch the fuzzer progress, but there is a lot of output, so you may want to pipe it out.

### Watch it in action
Open your browser to [http://127.0.0.1:26000/]() to see progress.

Watch the HTTP server under test to see if anything goes wrong.

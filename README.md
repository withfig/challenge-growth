# Fig Growth Challenge

* **Challenge 1**: Educational Twitter Thread
* **Challenge 2**: Autocomplete Spec video


# Challenge 1: Twitter Thread

1. Write an educational Twitter thread on something to do with bash / zsh / CLIs / terminals. 
2. Submit 5 other ideas that you brainstormed that would make great threads (just one-two sentences summarising each is plenty)

The aim of our educational Twitter threads is to get as many likes as possible. Why? Likes convert to followers. Followers continue to read other content we create, including content about Fig specifically. More eyeballs on Fig = more users. 

Our Twitter audience is comprised of very intellectually curious people. They are constantly learning and trying to improve themselves. We need to be interesting enough to attract advanced users but easy enough for everyone to understand. 

We think the thread should be at least 4 Tweets. This doesn't mean you need to have more than 4 tweets - if you can convey everything you need to know in just 4 tweets, that's great!

**Some examples of things that you could write about**
* Bash syntax:
  * Process substitution
  * Command substitution
  * Subshells
  * brace expansion
  * variable expansion
  * if statements!
* CLI tools
  * Popular unix CLI tools and what they do (e.g. "what is `sed`", "what is `awk`")
  * Popular modern CLI tools (e.g. `bat` vs `cat`)
  * Unknown but useful subcommands/options/flags in popular CLI tools (e.g. here is a subcommand in `git` that you probably didn't know about)
  * CLI tool history e.g. why are CLI tools slightly different on each operating system (e.g. bsd vs macOS)



<details>
  <summary><strong>Here is an example thread we've written up</strong></summary>
  
  <img width="694" alt="CleanShot 2022-03-18 at 17 29 56@2x" src="https://user-images.githubusercontent.com/4949076/159099507-4540e161-5fb4-4e61-9264-3bc6f8f1898a.png">
  <img width="604" alt="CleanShot 2022-03-18 at 17 31 44@2x" src="https://user-images.githubusercontent.com/4949076/159099550-1a0994e7-5137-4f72-bc2b-160db553e503.png">
<img width="601" alt="CleanShot 2022-03-18 at 17 32 04@2x" src="https://user-images.githubusercontent.com/4949076/159099560-c7ae6318-964a-42f3-b353-c0e0489840ea.png">
<img width="637" alt="CleanShot 2022-03-18 at 17 32 15@2x" src="https://user-images.githubusercontent.com/4949076/159099567-055231a0-1bba-428b-bfbe-380bcbc10bfc.png">
<img width="722" alt="CleanShot 2022-03-18 at 17 32 27@2x" src="https://user-images.githubusercontent.com/4949076/159099578-828393fc-8244-481b-b8d5-a1d7d15ee1ed.png">
<img width="618" alt="CleanShot 2022-03-18 at 17 32 38@2x" src="https://user-images.githubusercontent.com/4949076/159099588-ed3c7d19-7772-4737-bb75-523a4cb93ab3.png">

</details>

**Our suggestions**
* Don't write out your code in the tweet. Use screenshots of code blocks (check out [Carbon](https://carbon.now.sh/) or [ray.so](https://ray.so) and/or screenshots of your terminal (use a nice background and make sure text is readable)
* Keep tweets short and bite sized. No one wants to read a wall of text!
* The most interesting tweets have very useful and practical examples that the reader could add to their workflow instantly
* If you want to see what your Tweet Thread would look like live, check out https://typefully.com/ "High Fidelity mode"

**Inspiration for popular but complex shell topics**
* Popular guide for learning the terminal / shell: https://missing.csail.mit.edu/
* https://tldp.org/LDP/abs/html/


**Deliverables**
Please submit the following as a word docPDF 

1. A full Twitter thread for one of your ideas
2. 5 other ideas for threads you'd be excited to write about


# Challenge 2: Autocomplete Spec Video

Create a short video demo of you creating the `git` autocomplete spec. Your target audience is someone who has only just heard about Fig as a user and wants to build their own autocomplete. The aim of the video is to:

1. help developers set up their enviornment to create specs
2. teach the core concepts of a Fig completion spec (e.g. subcommand/options/arguments/generators) so if the developer wants to, they can continue on without us.
3. show a specific, well known example


**The git completion spec**
The git completion spec is huge. You obviously don't have to do the whole thing. Therefore, you should only create completions for the following:
* git checkout
* git checkout [branch]
   * You should generate suggestions for the branch using a "generator"
* git commit -m [msg]
 

**Resources**
 * Our getting started guide in https://fig.io/docs will be very very helpful.
 

**Other**
* Rather than using the cli named `git`, we suggest using a fake CLI named `abc`.
* You will need to write a "generator" for the <branch> argument. I will leave you to figure out what command to run to generate the suggestions and how to do the parsing.
* Keep the video clear, short and concise. Explain things like generators, options, subcommands, why you have the "args: { }" etc. Build it and test it live. Do a voice over. Can choose to show your face like in a loom or not at all.
* Doesn't need to be fully production ready, but also shouldn't be like a 10 min stream of consciousness talk. Have some structure. We think the video should be 3 - 5 min max!
 
 

# ChatBlocks-Examples

A collection of ChatBlocks examples, demos and templates that can be used with @Instafluff's ChatBlocks

- https://github.com/instafluff/ChatBlocks
- https://www.instafluff.tv/ChatBlocks/

# Using the examples

- download the `.cbs` file you want to try out
- navigate to https://www.instafluff.tv/ChatBlocks/ and sign in with your twitch account
- drag the `.cbs` file into the Blockly Editor window

# Contributing your examples and functions

I would love for you to contribute to this library of examples. Just keep these ideas things in mind:

- All examples and functions should be put into a folder. This will allow you to provide variant `.cbs` files as well as a `README.md` to explain any usage details or block limitations.
- Your `.cbs` file should only contain the blocks needed for that specific example or feature. If you have multiple examples that rely on reusable functions, consider saving those out as separate `.cbs` dependencies to include in your example folder. The point being to make it easier to add multiple examples to your ChatBlocks window without causing collisions.
- The goal is to make your blocks as portable as possible. Be verbose in your variable and function names to avoid collisions. Instead of `i` something like, `username_exampletitle_i`.
- Examples should not overly rely on variables. Variables in ChatBlocks are global. If your example needs to rely on variables, consider a very unique naming schema (see previous point).
- Add comments to your outer blocks to give hints and notes about how to properly use the block. To do this, right click the block and choose `Add Comment`
- Consider opening your `.cbs` files in a code editor and formatting them as XML. This will make it easier for folks to peruse and read your block code. By default, saving your `.cbs` files from ChatBlocks will be a less-readable minified string of xml.
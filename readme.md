# ANSWERS TO QUESTION NUM ONE
# The Event loop exist to process asynchronous task. It is also used for eecuting simple task such as callbacks and it runs this callbacks on a FIFO ideaology.

# ANSWERS TO QUESTION NUM TWO 
# Six phases of the event loop includes:
#   a. Timers- executes callbacks using timers. If there are timers set to 0 ms or setImmediate(), they will run here. Incomplete timers will run in later iterations of the loop.

#   b. Pending - internal phase
#   c. Idle/Prepare - internal phase
#   d. Poll - process I/O callbacks
#   e. Check - execute any setImediate() timers added in the Poll phase
#   f. Close - loop continues if there are more timers or I/O calls. If all timers and I/O calls are done, the loop closes and the process ends.

# ANSWERS TO QUESTION NUM THREE 
#  Best practices in server-side code development
#   a. Focus on code quality this includes; well-named variables, functions and comments.
#   b. Handle errors
#   c. Keep codes small
#   d. Use a formatter like Prettier for syntactical consistency.

# ANSWERS TO QUESTION NUM FOUR 
# NPM5 stands for Node Package Manager.

# # ANSWERS TO QUESTION NUM FIVE 
# npm init

# # ANSWERS TO QUESTION NUM SIX
# To run a script that you have added to your package.json file, simply run $ npm run argument with the name of the script as the argument. e.g :
# $ npm run prettier







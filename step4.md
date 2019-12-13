# Step 4: Dialogs

For this step, you're getting all the freedom you didn't ask for. Dialogs ensure that you can ask for input and the most common case for this is in cases where you need a slot filled.

When you edit an intent, you have the option to flag a slot as being required at which point you can use this to provide questions, sample answers, etc. Play around with this and make it all work.

Some general hints about this:
* If you have required slots in an intent, you can't also have utterances without that slot, without it triggering that question.
* If you want to have multiple handlers for the same intent, you will need to ensure that the `can_handle` functions in those handlers are different enough to differentiate between them. And remember that the order matters!
* Don't overcomplicate things, separate the intents and code into parts you can easily deal with.

[Next Step](step4.md)
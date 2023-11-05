# llm-real-time-voice-chat
Non-turn based real time voice chat with an LLM.


LLMs take the an entire conversation and output the next token. To construct the entire response this inference process occurs repeatadely until an end token is generated.

Components to this application:

- real time text-to-voice: to generate sound from the llm output
- real time voice-to-text: to translate the users voice into text
- clever prompt engineering: the LLM will need to be smart enough to understand that it is participating in a real time conversation



https://github.com/lm-sys/FastChat#vicuna-weights



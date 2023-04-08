Linux Implementation so might have issues elsewhere?

This a mix of HuggingGPT and ? so far

# main file - awesomechat - doesnt seem to have a interface yet

parse choose and respond
https://github.com/kwabs22/JARVIS/blob/87741149b3203535032db75e72648517ea267820/server/awesome_chat.py#L111

# HuggingGPT demo
https://github.com/kwabs22/JARVIS/blob/87741149b3203535032db75e72648517ea267820/server/run_gradio_demo.py#L93

# Models list
A jsonl file which is an index of the models on hugging face
https://github.com/kwabs22/JARVIS/blob/87741149b3203535032db75e72648517ea267820/server/awesome_chat.py#L123

The magic is how does it keep awareness of all the models and make a choice - does the user have to personally name the task
task labels help but I still have to test to understand
https://github.com/kwabs22/JARVIS/blob/87741149b3203535032db75e72648517ea267820/server/awesome_chat.py#L126

https://github.com/kwabs22/JARVIS/blob/87741149b3203535032db75e72648517ea267820/server/awesome_chat.py#L277

The real work!!
https://github.com/kwabs22/JARVIS/blob/87741149b3203535032db75e72648517ea267820/server/awesome_chat.py#L308
https://github.com/kwabs22/JARVIS/blob/87741149b3203535032db75e72648517ea267820/server/awesome_chat.py#L354

All tasks label in the comment and the if statements
https://github.com/kwabs22/JARVIS/blob/87741149b3203535032db75e72648517ea267820/server/awesome_chat.py#L358

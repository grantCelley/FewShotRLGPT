# Few Shot Learning Reinforcement Learning for GPT models

We first take a small model. In the first itteration of the software we will run [ElutherAI's GPT neo 125M](https://huggingface.co/EleutherAI/gpt-neo-125M). We train a classifier using [SetFit](https://huggingface.co/blog/setfit) to guide the output to what we want. Then we use the classifier to use Reinforcement learning to train the original model to generate helpful text. 

A sumery of what I am trying to do is from [Illustrating Reinforcement Learning from Human Feedback (RLHF)](https://huggingface.co/blog/rlhf).
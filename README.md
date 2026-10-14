# Harii Sankar

AI Engineer at Big Vision LLC, Bengaluru. I mostly build agentic applications, where a language model picks the tools and the next step.

## Work you can open

- [OpenCV pull request #27593](https://github.com/opencv/opencv/pull/27593), merged in August 2025. It added alpha-matting samples (cutting a person out of a photo) in C++ and Python. The model file the sample downloads is hosted in [Modnet](https://github.com/HarxSan/Modnet), my ONNX export of MODNet, published with the original license and credits.
- [opencv-pr-agent-rag](https://github.com/HarxSan/opencv-pr-agent-rag), a bot that reviews OpenCV pull requests. When someone comments `/review`, it looks up related OpenCV code in Qdrant and sends it with the diff to a Qwen 2.5 Coder 7B model that I fine-tuned on OpenCV review comments, with a colleague. It runs through [Qodo PR-Agent](https://github.com/The-PR-Agent/pr-agent). The repository has the commenting code, written in December 2025. The training code is not published, and review quality is not measured yet.
- [opencv-pr-data](https://huggingface.co/datasets/harxsan/opencv-pr-data), a public dataset on Hugging Face with 14,203 rows built from OpenCV pull request review comments, each with its code context. It is what the data work behind the bot produced.

## Elsewhere

- LinkedIn: [linkedin.com/in/harxsan](https://linkedin.com/in/harxsan)
- Hugging Face: [huggingface.co/harxsan](https://huggingface.co/harxsan)
- Blog: [harxsan.github.io](https://harxsan.github.io)
- Email: hariisankar720@gmail.com

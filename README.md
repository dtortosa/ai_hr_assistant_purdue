# AI-powered chatbot to answer HR questions

Project to learn the basics of building LLM applications within the context of the [Applied Generative AI Specialization](https://success.simplilearn.com/89e4e2d0-c691-4bf4-98b4-68543617056e#acc.MvROHITc).

In this project, I have processed a PDF with information about HR policies at Nestlé, generating as a result a storage that is searchable. Then, I have created a retriever using the storage and an instance of GTP3.5 turbo. This has been included in a chatbot that is able to ask for queries and return answers. It has different behaviors depending on whether the query is within the scope of the PDF or not. To handle this latter part, I have added a prompt template with Jinja2. All this has been wrapped in an user interface using Gradio. You can see all these steps with annotated code in the notebook named as [00_hr_chatbot.ipynb](./scripts/00_hr_chatbot.ipynb).

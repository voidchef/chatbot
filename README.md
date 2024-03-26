# ChatGPT Chatbot for PDF Files

Used GPT-3.5 api to build a doc chatbot for PDF files.

## Development

1. Clone the repo or download the ZIP

```
git clone [github https url]
```

2. Install packages

First run `npm install yarn -g` to install yarn globally (if you haven't already).

Then run:

```
yarn install
```

3. Set up your `.env` file

- Copy `.env.example` into `.env`
  Your `.env` file should look like this:

```
OPENAI_API_KEY=
PINECONE_API_KEY=
PINECONE_ENVIRONMENT=
PINECONE_INDEX_NAME=
PINECONE_NAME_SPACE=
```

## Convert your PDF files to embeddings

**This repo can load multiple PDF files**

1. Inside `docs` folder, add your pdf files.

2. Run the script `yarn run ingest` to 'ingest' and embed your docs.

## Run the app

Run the app `npm run dev` to launch the local dev environment, and then type a question in the chat interface.

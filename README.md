# CS224V Final Project

## Set up

1. Clone the repo
2. `cd` into the project directory
3. Install dependencies:

```bash
npm install
```

## How to run

1. If this is your first time running after downloading this repo, comment the line "cursor.execute("DROP TABLE documents")" in backend/backend.py and in App.js, highlight lines 37-48 and do CTRL+/. After running this application at least once, uncomment the line "cursor.execute("DROP TABLE documents")" in backend/backend.py
2. Run the command in the terminal:
```bash
python backend/backend.py
```

```bash
export NODE_OPTIONS=--openssl-legacy-provider
npx expo start --web
```

## Usage
1. Upload your pdf(s) to the server
2. Switch to a different pdf using the dropdown menu at the top of the left panel
3. Submit queries in the bottom left.  If you want to ask a question about the current document, click the blue send button.
    a. If you want to narrow down the set of documents, write your query and click the white filter icon. This will take a while to process (depending on the number of documents). The chat will indicate when it is ready. Then when you go to the dropdown menu you will see the narrowed down set of documents
    b. If you want to ask a question about the current document, click the blue send button. This will take a moment to process and then the pdf in the middle panel will refresh with the relevent sections highlighted.
    

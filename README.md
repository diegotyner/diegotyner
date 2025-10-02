# Hey there!

I'm **Diego Tyner**, a fourth year student at UC Davis double majoring in _Computer Science_ and _Cognitive Science_, with a minor in _Neuroscience_.

## Quick summary of projects

I mostly code things that are either personally useful to me (downloading online content, handling utilities like text extraction or fuzzy finding) or help me learn new technologies/frameworks (learning React/Next.js, learning ML python...).

### Interesting projects

#### Real Finder

While not my most complex, my favorite project is my Real Finder, a website I quickly scraped together so that I can quickly rifle through songs in the Jazz Real Book for quickly finding and learning new tunes!

- Used OCR to scan song names and page numbers, and then match and fuzzy find song names
- Works fully in HTML+JS, zero bloat (I can run it out of my local files no build).
- Take a look at the [code](https://github.com/diegotyner/Real-Finder) or the [demo](https://real-finder.vercel.app/)!
  - I'll likely expand it in the future with more features (and tunes of course).

#### YT Playlist Website

Probably my most clean technical project, I used Next.js and supabase to create a youtube playlist website to save youtube playlists to one place (since the official YT playlist interface kind of sucks).

- Take a look at the [code](https://github.com/diegotyner/YT-Playlist-Website) or the [demo](https://yt-playlist-website.vercel.app/)!
  - If I'm not planning to show it off it likely won't be active, since I have to activate the Supabase backend

#### News Dashboard

Another simple technical demo, more heavy on the backend Python AI side than the Next.js web dev side. Has a Next.js frontend, FastAPI dockerized Python backend, and dockerized pgvector PostgreSQL database. Has various features for quickly getting insights from recent news: scraping nad extraction, interactive dashboard, bias detection, snippet retrieval, RAG interaction, and NLP-based news summarization. This was a group summer project.

- Take a look at the [code](https://github.com/Lingotech-Davis/NewsDashboard) or the [demo](https://www.youtube.com/watch?v=KnU6oNDmrB8)!

#### Canvas Resource Semantic Search

Another scrappy project. This one I wrote so that I could scrape all of my course files before I graduate. A scraping pipeline including: selenium web scraper, concurrent downloading, and text extraction, embedding, storage and retrieval. Uses Selenium, Transformers (Mini-LM6), and pgvector PostgreSQL extension for embedding search.

- Take a look at the [code](https://github.com/diegotyner/CanvasResourceSemanticSearch)
  - This project could be extended, but I've moved onto other things

#### Deep Learning Code Repo

Code repo used for multi-stage deep learning group project. Includes MLP/SVM, CNN, RNN/GRU/LSTM, GNN. Learned various ML techniques in application: regularization, batching, feature engineering, and generally working with ML models.

- [Link](https://github.com/bkhli/ecs189g-ML)

### Rapid fire projects

Those were the demo projects I like to show off, here are other things I've built for personal use:

1. A [Hudl Downloader](https://github.com/diegotyner/Hudl_Downloader) that takes streamed data from Hudl and downloads it locally. Python based.
2. A [Libby Downloader](https://github.com/diegotyner/LibbyDownloader) that takes streamed data from Libby audiobooks and downloads it locally. Chrome extension based (for evading detection).
3. A web hosted [OCR text extractor](https://github.com/diegotyner/handwriting-wrapper) wrapper for the OCR.space text recognition API. Very helpful for quickly getting text from screenshots of images.
4. Forked quartz so that I could have a [Obsidian Vault Deployment](https://github.com/diegotyner/Vault-Deployment). Useful for sending classmates a link to notes. Probably the closest I have to a portfolio website.
5. Public deployment of a [NBA playoffs game searching website](https://github.com/diegotyner/PublicBasketballWebsite). I used it to search through Youtube videos for other reasons (feel free to ask!) and cloned it for a public deployment.

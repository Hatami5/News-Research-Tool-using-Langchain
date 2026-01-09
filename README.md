<h1 align="center">📰 News Research Tool 📈</h1> <p align="center"> <b>Explore, analyze, and compare news articles using AI — interactively.</b><br> Built and maintained by <a href="https://github.com/Hatami5">Hassan Hatami</a> • AI Developer @ SageMind Tech Services </p>
<h2> Overview</h2> <p> <b>News Research Tool</b> is an AI-powered, interactive web app that helps you explore and summarize multiple news articles effortlessly. Paste up to <b>three news URLs</b>, ask <b>natural language questions</b>, and get <b>concise answers with sources</b> — powered by <b>Streamlit</b>, <b>LangChain</b>, and <b>OpenAI</b>. </p> <blockquote>  Designed for journalists, analysts, and curious readers who want clarity — instantly. </blockquote>
<h2> Key Features</h2> <ul> <li>🔗 <b>Multi-URL Input</b> — Analyze up to 3 news articles together.</li> <li> <b>Automated Content Processing</b> — Fetch, clean, and analyze articles instantly.</li> <li> <b>Natural Q&A</b> — Ask questions like “What’s the main idea?” or “How do these articles differ?”</li> <li> <b>AI + Vector Search</b> — Uses OpenAI embeddings + FAISS for semantic understanding.</li> <li> <b>Cited Responses</b> — Provides answers with referenced source links.</li> <li> <b>Local Reuse</b> — Saves embeddings in <code>faiss_store_openai.pkl</code> for faster queries.</li> </ul>
<h2> Tech Stack</h2> <table> <tr><th>Tool / Framework</th><th>Purpose</th></tr> <tr><td><b>Python 3.9+</b></td><td>Core programming language</td></tr> <tr><td><b>Streamlit</b></td><td>Interactive UI for live exploration</td></tr> <tr><td><b>LangChain</b></td><td>LLM orchestration and chaining</td></tr> <tr><td><b>OpenAI API</b></td><td>GPT models + text embeddings</td></tr> <tr><td><b>FAISS</b></td><td>Vector similarity search</td></tr> <tr><td><b>Pickle</b></td><td>Persistent local data storage</td></tr> <tr><td><b>dotenv</b></td><td>Secure API key management</td></tr> </table>
<h2> Setup Instructions</h2> <h3>1️⃣ Clone the Repository</h3>
git clone https://github.com/Hatami5/Chatbot-using-Langchain.git
cd news-research-tool
<h3>2️⃣ Install Dependencies</h3>
pip install -r requirements.txt

<h3>3️⃣ Add Your OpenAI API Key</h3>

Create a <code>.env</code> file in the project root:

OPENAI_API_KEY=your_openai_api_key_here

<h3>4️⃣ Run the App</h3>
streamlit run app.py

<h2> How to Use</h2> <ol> <li>Open <a href="http://localhost:8501">http://localhost:8501</a>.</li> <li>Enter up to <b>3 news URLs</b> in the sidebar.</li> <li>Click <b>Process URLs</b> to load and embed the content.</li> <li>Ask any <b>natural language question</b> about the articles.</li> <li>Get <b>AI-powered insights</b> with <b>linked sources</b>.</li> </ol>
<h2> Example Interaction</h2> <p><b>Question:</b><br> <i>What’s the main takeaway from these articles?</i></p> <p><b>Answer:</b><br> The articles highlight the global impact of rising energy prices and inflation trends.</p> <p><b>Sources:</b></p> <ul> <li><a href="https://example-news1.com">https://example-news1.com</a></li> <li><a href="https://example-news2.com">https://example-news2.com</a></li> </ul>
<h2> Future Enhancements</h2> <ul> <li> Support more than 3 URLs</li> <li> Multi-language news support</li> <li> Real-time live news updates</li> <li> Deploy on Streamlit Cloud / HuggingFace Spaces</li> </ul>
<h2 align="center"> Author</h2> <p align="center"> <b>Hassan Hatami</b><br> AI/ML Engineer | Automation Expert |AI workflow | NLP Engineer<br> <a href="https://github.com/Hatami5">GitHub</a> • <a href="https://www.linkedin.com/in/hassan-hatami">LinkedIn</a> </p>
<p align="center"> ⭐ <b>If you like this project, don’t forget to star the repo and share it!</b> ⭐ </p>

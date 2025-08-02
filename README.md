<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>

  <h1>🌍 Social Media Summary Generator</h1>
  <p><strong>Powered by LangChain + Google GenAI + DuckDuckGo Search</strong></p>

  <div class="section">
    <p>This project uses real-time search, AI summarization, and prompt engineering to automate creation of social media content across platforms.</p>
    <ul>
      <li>🔍 Search live news or web content</li>
      <li>📄 Generate concise summaries</li>
      <li>📢 Create tailored social media posts for LinkedIn, Facebook, and Twitter/X</li>
    </ul>
  </div>

  <div class="section">
    <h2>✅ Features</h2>
    <ul>
      <li>Real-time content search via DuckDuckGo</li>
      <li>AI summarization using Gemini 1.5 (Google GenAI)</li>
      <li>Multi-platform post generation: LinkedIn, Facebook, Twitter</li>
      <li>Parallel execution with LangChain for efficiency</li>
    </ul>
  </div>

  <div class="section">
    <h2>🔑 Requirements</h2>
    <ul>
      <li>LangChain and LangChain Community packages</li>
      <li>Google Generative AI access (API Key required)</li>
      <li>Internet access for search functionality</li>
    </ul>
  </div>

  <div class="section">
    <h2>🛠️ How It Works</h2>
    <ol>
      <li>User provides a search topic (e.g., “India vs Pakistan war 2025”)</li>
      <li>DuckDuckGo fetches relevant web content</li>
      <li>Gemini summarizes the information into bullet points</li>
      <li>LangChain generates platform-specific posts using prompt templates</li>
    </ol>
  </div>

  <div class="section">
    <h2>Example Output</h1>
<p>
  For LinkedIn, the post is titled “The 2025 India-Pakistan Conflict: A Wake-Up Call for Geopolitical Strategists”, offering a professional and insightful analysis of the triggers, intensity, and key lessons from the short but impactful conflict. It uses hashtags like #Geopolitics, #ConflictResolution, #StrategicStudies, and #SouthAsia.
On Facebook, the tone is more engaging with the title “🤯 A Month That Shook the World: The 2025 India-Pakistan Conflict”, summarizing how escalating tensions turned into a crisis, highlighting its relevance today, and featuring hashtags such as #IndiaPakistanConflict, #Geopolitics, #GlobalSecurity, and #SouthAsia.
The Twitter/X version is succinct: “India-Pakistan conflict (May–June 2025): A month of intense military engagement sparked by terror and long-standing tensions”, accompanied by hashtags like #IndiaPakistanConflict, #Geopolitics, and #InternationalRelations.


</p>
  </div>

  <div class="section">
    <h2>🌐 Use Cases</h2>
    <ul>
      <li>Social media automation for newsrooms</li>
      <li>Content generation for analysts and strategists</li>
      <li>Educational summaries for students and researchers</li>
      <li>Marketing and awareness campaigns</li>
    </ul>
  </div>

  <div class="section">
    <h2>📋 Output Format</h2>
    <p>The final output is returned as a dictionary with keys:</p>
    <ul>
      <li><code>linkedin</code> — Insightful long-form post</li>
      <li><code>fb</code> — Engaging, emoji-rich post</li>
      <li><code>twitter</code> — Concise post within 280 characters</li>
    </ul>
  </div>

</body>
</html>


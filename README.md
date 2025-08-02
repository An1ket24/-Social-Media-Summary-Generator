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
    <h2>📌 Example Output</h2>

    <h3>🔗 LinkedIn</h3>
    <p><strong>The 2025 India-Pakistan Conflict: A Wake-Up Call for Geopolitical Strategists</strong></p>
    <p>A professional, insightful post analyzing the triggers, intensity, and lessons from the brief but significant conflict.</p>
    <p><em>Hashtags:</em> #Geopolitics #ConflictResolution #StrategicStudies #SouthAsia</p>

    <h3>📘 Facebook</h3>
    <p><strong>🤯 A Month That Shook the World: The 2025 India-Pakistan Conflict</strong></p>
    <p>An engaging breakdown of how tensions escalated and why it matters now more than ever.</p>
    <p><em>Hashtags:</em> #IndiaPakistanConflict #Geopolitics #GlobalSecurity #SouthAsia</p>

    <h3>🐦 Twitter/X</h3>
    <p><strong>India-Pakistan conflict (May–June 2025):</strong> A month of intense military engagement sparked by terror and long-standing tensions.</p>
    <p><em>Hashtags:</em> #IndiaPakistanConflict #Geopolitics #InternationalRelations</p>
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


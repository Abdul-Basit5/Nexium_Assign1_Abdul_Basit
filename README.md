<h1>💡 Quote Generator Web App</h1>
<p>A <strong>React + TypeScript web application</strong> that generates inspiring quotes based on user-entered topics like <strong>life, success, motivation, love, wisdom</strong>, and more. Built using <strong>Vite, Express.js, ShadCN UI</strong>, and <strong>Tailwind CSS</strong>, it offers a fast, clean, and responsive user experience.</p>

<h2>📌 Features</h2>
<p><strong>• Topic-based Quote Generation:</strong> Get 3 hand-picked quotes by entering any topic.</p>
<p><strong>• 250+ Curated Quotes:</strong> Preloaded local JSON containing quotes from renowned authors.</p>
<p><strong>• Responsive Design:</strong> Optimized for desktop, tablet, and mobile views.</p>
<p><strong>• ShadCN UI Integration:</strong> Styled with modern components and Radix UI.</p>
<p><strong>• Favorites System:</strong> Mark quotes you love with an interactive heart button.</p>
<p><strong>• Share Functionality:</strong> Use native sharing or copy quotes to clipboard.</p>
<p><strong>• Popular Topics:</strong> Instant buttons for trending quote categories.</p>

<h2>🖥️ How to Use</h2>
<p><strong>1.</strong> <strong>Enter a Topic:</strong> Type a topic like “life” or “motivation”.</p>
<p><strong>2.</strong> <strong>Generate Quotes:</strong> Click “Generate Quotes” to view 3 inspiring results.</p>
<p><strong>3.</strong> <strong>Favorite/Share:</strong> Click the heart to favorite or share quotes instantly.</p>
<p><strong>4.</strong> <strong>Try Categories:</strong> Tap on a popular category for quick results.</p>

<h2>🔧 Key Components</h2>
<p><strong>• Header / Footer:</strong> Responsive layout with branding and attribution.</p>
<p><strong>• QuoteCard:</strong> Displays a styled individual quote with color variant.</p>
<p><strong>• API Endpoint:</strong> <code>/api/quotes/:category</code> returns quotes from the server.</p>
<p><strong>• Local JSON:</strong> Quote content is stored locally for blazing-fast speed.</p>
<p><strong>• useToast():</strong> Handles user notifications (e.g., empty input, copied alert).</p>

<h2>⚙ Technology Stack</h2>
<p><strong>• Frontend:</strong> React, TypeScript, Vite, ShadCN UI, Tailwind CSS, Lucide Icons</p>
<p><strong>• Backend:</strong> Node.js, Express, TypeScript</p>
<p><strong>• State:</strong> TanStack Query (React Query)</p>
<p><strong>• Routing:</strong> Wouter (lightweight alternative to React Router)</p>

<h2>▶ How to Run the Project</h2>
<p><strong>1.</strong> Clone the repo:</p>
<pre><code>git clone &lt;your-repo-url&gt;</code></pre>
<p><strong>2.</strong> Install dependencies:</p>
<pre><code>npm install</code></pre>
<p><strong>3.</strong> Start development server:</p>
<pre><code>npm run dev</code></pre>
<p><strong>4.</strong> For production build:</p>
<pre><code>npm run build && npm start</code></pre>

<h2>🌐 API Endpoints</h2>
<ul>
  <li><code>GET /api/quotes/:category</code> – Fetch quotes by topic</li>
  <li><code>GET /api/categories</code> – List available categories</li>
  <li><code>GET /api/quotes?q=search</code> – Search quotes (if search enabled)</li>
</ul>

<h2>🚀 Project Impact</h2>
<p>This web application improves understanding of <strong>frontend/backend integration, modern UI/UX design, REST APIs</strong>, and real-time interactivity using <strong>React Query</strong>. It's perfect for demonstrating how a full-stack project works with local data and responsive features.</p>

<p>Let me know if you need enhancements or deployment help! 💬</p>

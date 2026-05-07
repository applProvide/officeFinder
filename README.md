# OfficeFinder
### 🌐 [English](README.md) | [한국어](README.ko.md) | 📦 [Install Guide](INSTALL.md)

<h1>Integrated Document Search Program (Multi-format Context-Based Document Search Engine)</h1>
<h2>Search across multiple document types in one unified system</h2>
  • Full support for Excel, Word, PDF, and HWP  
  • Precise data extraction with group-based conditional search  
  • High accuracy through keyword + context analysis  

👉 A next-generation document search solution that boosts productivity


<ul>
  <li>Full support for Excel, Word, PDF, PPT, and HWP</li>
  <li>Precise data extraction with group-based conditional search</li>
  <li>High search accuracy through keyword + context analysis</li>
  <li>Goes beyond simple keyword matching by analyzing relationships and context between words</li>
  <li>Search scattered documents in one place</li>
  <li>Advanced search that analyzes the context before and after specific words</li>
  <li>Extracts text from various document formats and integrates them into a single searchable system</li>
</ul>

<h3>1. Overview</h3>
<h4>This program is an advanced condition-based integrated document search system designed to quickly extract desired information from various document files.</h4>
<h4>Beyond simple keyword search, it improves accuracy by analyzing the **context (surrounding words)** of specific terms.</h4>

<h3>2. Key Features</h3>

<h4>2.1 Group-Based Search System</h4>
<ul>
  <li>Search conditions can be organized into groups</li>
  <li>Each group has independent conditions and is combined during overall search</li>
  <li>Complex conditions can be logically structured</li>
  <li>Supports AND / OR logical expansion</li>
  <li>Highlights search results</li>
</ul>

<h4>2.2 Keyword + Context-Based Search</h4>
<ul>
  <li>Improves accuracy by analyzing the context before and after keywords</li>
  <li>Basic keyword search – checks for the presence of specific terms</li>
  <li>Context expansion search – searches surrounding words based on a keyword</li>
  <li>
    • Search for the word “contract”<br />
    • “contract” + preceding word: “electronic”<br />
    • “contract” + following word: “execution”<br />
    → Accurately detects context such as “electronic contract execution”
  </li>
  <li>Reduces false positives</li>
  <li>Provides results closer to actual document content</li>
</ul>

<h4>2.3 Support for Multiple Document Formats</h4>
<ul>
  <li>Excel  : .xls, .xlsx</li>
  <li>Word   : .doc, .docx</li>
  <li>PDF    : .pdf</li>
  <li>PowerPoint : .ppt, .pptx</li>
  <li>HWP (Hangul) : .hwp, .hwpx</li>
  <li>Text : .txt, .xml, .js, .py, .csv, .log, .html, .htm, .css, .java, .cpp, .c, .json, .yaml, .yml, .bat, .sh</li>
</ul>
<ul>
  <li>Processes multiple formats within a single search system</li>
  <li>Provides a consistent search experience regardless of file type</li>
</ul>

<h4>2.4 Multi-Condition Combined Search</h4>
<ul>
  <li>Performs complex searches by applying multiple groups simultaneously</li>
  <li>e.g.) (contract-related keywords) AND (includes amount) AND (specific context)</li>
  <li>Extracts only the required information accurately</li>
  <li>Fast filtering even in large volumes of documents</li>
</ul>

<h4>2.5 User Convenience Features</h4>
<ul>
  <li>Intuitive UI-based condition configuration</li>
  <li>Condition retention for repeated searches</li>
  <li>Fast search performance</li>
  <li>Ability to locate matching documents and positions</li>
</ul>

<h3>3. Core Technologies</h3>

<h4>✔ Context-Based Search Algorithm</h4>
<ul>
  <li>Sentence structure-based search rather than keyword-only matching</li>
  <li>Considers relationships between words</li>
</ul>

<h4>✔ Multi-format Parsing Processing</h4>
<ul> 
  <li>Applies data extraction logic for each document format</li>
  <li>Converts into unified text data for integrated searching</li>
</ul>

<h3>4. Use Cases</h3>
<ul>
  <li>📑 Contract / legal document search</li>
  <li>📊 Extracting specific content from reports</li>
  <li>🏢 Internal document integration search system</li>
  <li>🔎 Keyword-based auditing and verification tasks</li>
</ul>

<section>
  <h1>User Manual (End-User Guide)</h1>

  <section>
    <h2>1. Main Screen Overview</h2>
    <div>
      <img width="804" height="458" alt="image" src="https://github.com/user-attachments/assets/4eab18ad-5ad7-4369-b37a-d70bc5cf1b24" />
    </div>
    <ol>
      <li>Create a new project</li>
      <li>Search conditions are displayed</li>
      <li>Start searching based on selected conditions</li>
      <li>Created projects are listed, allowing edit/delete/search condition setup</li>
      <li>Displays folders and file list of the selected project</li>
      <li>Single-click shows file on the right, double-click opens it on your PC</li>
      <li>Document file name</li>
    </ol>
  </section>

  <section>
    <h2>2. Creating a Project</h2>
    <h3>Click the [Create New Project] button to create a project.</h3>
    <div>
     <img width="460" height="376" alt="image" src="https://github.com/user-attachments/assets/a7033792-b400-42bb-9c6e-d9ff93edc60d" />
    </div>
    <ol>
      <li>Enter the project name</li>
      <li>Add folders to include in search conditions</li>
      <li>Add files to include in search conditions</li>
      <li>Save the project</li>
      <li>Delete added folders or files</li>
    </ol>
  </section>

  <section>
    <h2>3. Creating Search Conditions</h2>
    <h3>Click the [Search Conditions] button in the selected project to create conditions.</h3>
    <div>
     <img width="723" height="422" alt="image" src="https://github.com/user-attachments/assets/7ff89ca2-57d0-4b04-b671-1726607d99ac" />
    </div>
     <ol>
      <li>Create a new search condition</li>
      <li>Save the search condition</li>
      <li>Copy the selected condition (copied name appears on the left)</li>
      <li>Delete the selected condition</li>
      <li>Displays created search conditions</li>
      <li>Join groups using AND / OR</li>
      <li>Add groups to include in the search</li>
      <li>Define operations for conditions within a group</li>
      <li>Enter search keywords</li>
      <li>Enter the number of characters to expand before/after the keyword (numbers only)</li>
      <li>Enter additional keywords separated by commas (e.g., John, Smith)</li>
      <li>Join additional keywords using AND / OR</li>
    </ol>
  </section>
</section>

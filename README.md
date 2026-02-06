# TASK 1 "Query-Driven Causal Explanation with Evidence"
#  Simple Conversation Analyzer

## What This Does
Analyzes customer service conversations to find out **why bad things happen** (like escalations, refunds, angry customers).

---

##  Two Super Simple Ways to Use

### Option 1: Interactive Web Dashboard (RECOMMENDED)
**Best for:** Everyone! Easy point-and-click interface.

```
python interactive_analyzer.py
```

**What happens:**
1. Program loads your conversations
2. Web browser opens automatically
3. You see a beautiful dashboard
4. Click any outcome to analyze it
5. See why it happens with real examples!

**Features:**
- Search for specific outcomes
- See top 15 most common problems
- Get instant analysis with graphs
- Read real customer quotes as evidence
- No coding needed!

---

### Option 2: Command Line Version
**Best for:** Quick stats and simple analysis.

```
python simple_analyzer.py
```

**What you get:**
- Statistics about all conversations
- Analysis of specific outcomes
- Example evidence from real chats
- HTML dashboard file created

---

##  What You'll See

### Dashboard Shows:
1. **Total Conversations**: How many chats analyzed
2. **Different Outcomes**: Types of results (escalation, refund, etc.)
3. **Top Outcomes**: Most common problems
4. **Search Box**: Find specific issues

### When You Click an Outcome:
1. **Why It Happens** - The main reasons
   - Frustrated customers
   - Legal threats
   - Repeated problems
   - Long wait times
   
2. **Real Evidence** - Actual customer quotes
   - "This is the third time I've called!"
   - "I'm going to contact my lawyer"
   - "I've been waiting for weeks"

---

##  Dashboard Features

### What You Can Do:
- **Click** any outcome to analyze it
- **Search** for specific problems
- **See percentages** - How often things happen
- **Read examples** - Real conversation snippets
- **No programming** - Just point and click!

---

##  Example Usage

### Finding Why Customers Get Angry:

1. Run the program:
   ```
   python interactive_analyzer.py
   ```

2. Wait for browser to open

3. Click "Escalation - Threat of Legal Action"

4. See results like:
   ```
   Why This Happens:
   • Frustrated: 15 times (45% of cases)
   • Legal Threat: 8 times (24% of cases)
   • Repeated Issue: 12 times (36% of cases)
   
   Evidence:
   Customer: "I'm extremely frustrated!"
   Customer: "I'm contacting my lawyer"
   Customer: "Third time calling about this!"
   ```

---

##  What Gets Analyzed

### The System Looks For:

**Angry Words**
- frustrated, angry, upset, furious

**Legal Threats**
- lawyer, lawsuit, legal action, sue

**Repeated Problems**
- third time, already told you, mentioned before

**Long Waits**
- weeks, months, still waiting, long time

**Want Manager**
- supervisor, manager, escalate

---

##  Understanding Results

### Signal Cards Show:
- **Number**: How many times this happened
- **Percentage**: What % of conversations

Example:
```
Frustrated: 15
45% of cases
```
Means: In 45% of these conversations, customers said they were frustrated.

### Evidence Boxes Show:
- **Who said it**: Customer or Agent
- **What they said**: Exact quote from conversation

---

##  Tips for Best Results

1. **Start with Search**
   - Type keywords like "fraud", "escalation", "refund"
   - See matching outcomes instantly

2. **Check Top Outcomes First**
   - These are the most common problems
   - Biggest impact on your business

3. **Read the Evidence**
   - Real quotes show exactly what went wrong
   - Use for training agents

4. **Look at Percentages**
   - High % = very common problem
   - Low % = rare but important

---

##  Requirements

**You Need:**
- Python 3.6 or newer
- The conversation data file (JSON)
- A web browser

**That's It!**


##  Files Included

1. **interactive_analyzer.py** - Main program (web dashboard)
2. **simple_analyzer.py** - Command line version
3. **dashboard.html** - Static HTML (created by simple version)

##  Next Steps

1. **Run the analyzer**
   ```
   python interactive_analyzer.py
   ```

2. **Explore different outcomes**
   - Click around
   - Search for patterns
   - Read customer quotes

3. **Take action**
   - Train agents on common issues
   - Fix repeated problems
   - Improve processes

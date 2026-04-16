# Examples: Before and After

Real examples of how these principles change Claude Code's output when helping with YouTube content.

---

## Principle 1: Packaging First

### Before (without guidelines)

**You:** "Help me make a video about AWS cost optimization"

**Claude:** "Here's a script outline for 'AWS Cost Optimization Tips'..."

### After (with guidelines)

**You:** "Help me make a video about AWS cost optimization"

**Claude:** "Before we script anything, let's nail the packaging. Here are 10 title options ranked by ceiling:

1. 'AWS Charged Me $14,000. Here's How I Got It to $400' (Curiosity + Fear, 48 chars, IMPACT: 26/30)
2. 'Stop Overpaying for AWS — The $0 Fix Nobody Uses' (Desire + Curiosity, 50 chars, IMPACT: 24/30)
3. ...

Thumbnail direction for #1: Close-up face with shock expression, AWS bill showing $14,000 crossed out, '$400' in large yellow text. Dark background for dark mode."

**Why it's better:** The packaging is conceived first. The video will be built to deliver on whichever title wins.

---

## Principle 2: Earn Every Second

### Before

```
0:00 - "Hey everyone, welcome back to the channel. Today we're going to talk about
        something really interesting. So I've been working with AWS for a while now
        and I wanted to share some tips..."
```

### After

```
0:00 - [Screen: AWS bill showing $14,000]
        "This is my real AWS bill from last month. Fourteen thousand dollars.
         And this—" [cut to bill showing $400] "—is this month. Same workload.
         Here's exactly what I changed."

0:25 - [Pattern interrupt: quick zoom, music shift]
        "By the end of this video, you'll know the 4 things eating your AWS budget
         and how to fix each one in under an hour."
```

**Why it's better:** Value in 5 seconds. Promise delivered immediately. Zero filler before the hook. Pattern interrupt at 25 seconds.

---

## Principle 3: Copy With Taste

### Before

**You:** "What video should I make next?"

**Claude:** "Here are some ideas:
- 'How to Use AWS Lambda'
- 'Introduction to Terraform'
- 'Cloud Computing Explained'"

### After

**You:** "What video should I make next?"

**Claude:** "Let me check outliers in your niche first.

Outlier found: 'I Tried Every Cloud Provider So You Don't Have To' — 847K views on a 50K-subscriber channel (17x above average). Format: comparative test with personal narrative.

Your adaptation: 'I Ran the Same App on AWS, Azure, and GCP. The Bill Was Insane.'
- Same format (comparative test), your niche (cost), your voice (ex-Amazon insider)
- Thumbnail: three cloud logos with price tags, your face showing shock at the biggest one"

**Why it's better:** Idea grounded in proven demand, not guesswork. Format extracted from an outlier. Adapted to the creator's unique angle.

---

## Principle 4: Kill or Ship

### Before

**You:** "I filmed a video about Docker basics. Help me upload it."

**Claude:** "Here's a title and description for your Docker basics video..."

### After

**You:** "I filmed a video about Docker basics. Help me upload it."

**Claude:** "Let me run the quality gates first:

| Gate | Status | Issue |
|------|--------|-------|
| 1. Title Click Trigger | FAIL | 'Docker Basics' has no curiosity, desire, or fear trigger |
| 2. Thumbnail-Title Synergy | FAIL | Need to see thumbnail |
| 3. First 5 Seconds | ? | What's the opening? |
| 4. Satisfaction Delivery | PASS | Tutorial delivers what it promises |
| 5. Retention Architecture | ? | Need to review edit |
| 6. Subscribe-Worthy | FAIL | 'Docker basics' exists from 500 other channels |
| 7. Format Validation | FAIL | No outlier evidence for this format in your niche |
| 8. Personal Excitement | ? | Are you excited about this? |

Score: 1/8 confirmed pass, 3 unknown, 4 fails.

**Recommendation: KILL or repackage.** The ceiling is too low. Consider: 'I Deployed My App with Docker in 4 Minutes (No Tutorials Needed)' — same content, 10x the packaging."

**Why it's better:** Weak video caught before it damages the channel. Repackaging suggestion saves the work while raising the ceiling.

---

## Principle 5: Obsess the Viewer

### Before

**You:** "I want to make a series about Kubernetes."

**Claude:** "Great! Here's a 10-part Kubernetes series outline..."

### After

**You:** "I want to make a series about Kubernetes."

**Claude:** "Before we outline, let me ask about your viewer:

1. What's their biggest frustration with Kubernetes right now? (DevOps engineer who inherited a cluster? Manager trying to understand costs? Developer forced to learn it?)
2. What do they NOT want? (Theory-heavy lectures? Basic 'what is a pod' content they've seen 50 times?)
3. What would make them subscribe after episode 1?

Also: the 2026 algorithm prioritizes series formats. If we structure this as a numbered series with consistent packaging, YouTube will actively promote later episodes to people who watched earlier ones.

And one data point: educational content gets 80% of its views 6+ months after upload. This series will compound. Let's make episode 1 strong enough to carry the rest."

**Why it's better:** Starts with the viewer, not the topic. Uses algorithm knowledge (series priority). Sets expectations for long-term compounding.

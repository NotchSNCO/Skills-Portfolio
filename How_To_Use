# How to Use This Portfolio Repository

## 📖 What You Have

This is a complete **8-week intensive cloud security upskilling program** designed to take you from security generalist to cloud-native application security engineer.

## 📁 File Structure

### Core Documents (Start Here)
1. **README.md** - Main portfolio overview and progress tracker
2. **QUICK_START.md** - Installation, setup, and daily routine guide  
3. **PROGRAM_SUMMARY.md** - Complete 8-week syllabus summary
4. **THIS FILE (HOW_TO_USE.md)** - You are here!

### Weekly Guides
Each week has its own directory with detailed step-by-step guides:

- `week-01-aws-security/README.md` - **FULLY COMPLETE** ✅ (18,000+ words of detailed instructions)
- `week-02-terraform-iac/README.md` - Summary provided, expand as you go
- `week-03-docker-security/README.md` - Summary provided
- `week-04-kubernetes-security/README.md` - Summary provided
- `week-05-cicd-security/README.md` - Summary provided
- `week-06-eks-cloud-native/README.md` - Summary provided
- `week-07-advanced-patterns/README.md` - Summary provided
- `week-08-capstone/README.md` - Summary provided

## 🚀 Getting Started (First Steps)

### Step 1: Fork and Clone
```bash
# On GitHub: Click "Fork" button
# Then clone YOUR fork
git clone https://github.com/YOUR_USERNAME/cloud-security-upskill-portfolio.git
cd cloud-security-upskill-portfolio
```

### Step 2: Read Core Documents (1 hour)
1. Read `README.md` - Understand the program
2. Read `QUICK_START.md` - Set up your environment
3. Read `PROGRAM_SUMMARY.md` - See all 8 weeks
4. Bookmark all docs for reference

### Step 3: Install Prerequisites (2-3 hours)
Follow `QUICK_START.md` to install:
- AWS CLI
- Terraform  
- Docker
- kubectl
- Minikube
- Security tools (checkov, trivy, etc.)

### Step 4: Set Up AWS Account (1 hour)
- Create AWS free tier account
- Configure AWS CLI with credentials
- Set up billing alerts

### Step 5: Start Week 1 (20-25 hours over 7 days)
```bash
cd week-01-aws-security
cat README.md  # Read the complete guide
# Follow step-by-step instructions
```

## 📚 How to Use Each Week

### Week 1 Example (Pattern for All Weeks)

1. **Read the README.md first** (30 minutes)
   - Understand objectives
   - Review deliverables
   - Check prerequisites

2. **Follow daily breakdown** (2-4 hours/day)
   - Execute commands step-by-step
   - Verify results
   - Take screenshots
   - Document findings

3. **Create documentation** (daily)
   - Save outputs
   - Write explanations
   - Update progress tracker
   - Commit to GitHub

4. **Complete deliverables** (end of week)
   - Review checklist
   - Self-assessment
   - Update portfolio README
   - Prepare for next week

## 💻 Daily Workflow

### Morning (30 min)
```bash
# Review yesterday's work
git log --oneline -5

# Plan today
cat week-01-aws-security/README.md | grep "Day X"

# Update status
vim README.md  # Update progress tracker
```

### Work Session (2-4 hours)
```bash
# Open the guide
cd week-XX-topic
cat README.md

# Follow instructions
aws cloudtrail create-trail ...  # Example command
terraform apply                   # Example command

# Document as you go
vim notes.md  # Write what you learned
```

### Evening (30 min)
```bash
# Commit your work
git add .
git commit -m "Week X Day Y: Completed [topic]"
git push origin main

# Update progress in main README
vim README.md  # Mark tasks complete ✅
```

## 📝 Documentation Best Practices

### What to Document
1. **Commands executed** - Copy/paste with outputs
2. **Errors encountered** - And how you fixed them
3. **Concepts learned** - In your own words
4. **Screenshots** - Dashboards, results, configs
5. **Questions** - Track what you want to learn more about

### How to Document

Create a file for each day:
```bash
week-01-aws-security/
├── README.md                     # Main guide (provided)
├── day1-notes.md                 # Your notes
├── day2-notes.md
├── screenshots/
│   ├── security-hub-dashboard.png
│   └── guardduty-findings.png
└── code/
    ├── lambda-function.py
    └── terraform/
```

### Documentation Template
```markdown
# Week X Day Y: Topic

## What I Did Today
- [ ] Task 1
- [ ] Task 2  
- [ ] Task 3

## Commands Executed
` ``bash
aws cloudtrail get-trail-status --name my-trail
# Output: [paste output]
` ``

## What I Learned
- CloudTrail provides ...
- GuardDuty detects ...

## Challenges
- Error: Access Denied
- Solution: Updated IAM policy

## Questions for Later
- How does GuardDuty ML work internally?
- Best practices for multi-region trails?

## Screenshots
![Security Hub Dashboard](screenshots/security-hub.png)

## Status
✅ Complete | 🟡 In Progress | ⬜ Not Started
```

## 🎯 Progress Tracking

### Update Main README Daily
In the root `README.md`, update the progress tracker:

```markdown
| Week | Focus Area | Status | Completion Date |
|------|-----------|--------|-----------------|
| 1 | AWS Security | 🟡 In Progress | - |
| 2 | Terraform | ⬜ Not Started | - |
```

Change to:
```markdown
| Week | Focus Area | Status | Completion Date |
|------|-----------|--------|-----------------|
| 1 | AWS Security | ✅ Completed | 2025-02-15 |
| 2 | Terraform | 🟡 In Progress | - |
```

### Create Weekly Retrospectives
At the end of each week, create `week-XX-retrospective.md`:

```markdown
# Week X Retrospective

## Achievements
- Completed X exercises
- Built Y projects  
- Learned Z concepts

## Challenges
- Struggled with [topic]
- Spent extra time on [topic]

## Key Learnings
1. [Learning 1]
2. [Learning 2]
3. [Learning 3]

## Time Spent
- Estimated: 25 hours
- Actual: 28 hours
- Difference: +3 hours (due to troubleshooting)

## Next Week
- Focus areas
- Prerequisites needed
- Questions to answer
```

## 💡 Tips for Success

### 1. Commit Often
```bash
# Minimum once per day
git add .
git commit -m "Descriptive message"
git push

# Better: Multiple times per day
git commit -m "Day 1: Completed CloudTrail setup"
git commit -m "Day 1: Fixed S3 bucket policy error"
git commit -m "Day 1: Finished security baseline"
```

### 2. Don't Skip Documentation
Even if you think "I'll remember this":
- You won't
- Future employers want to see it
- Helps you learn by writing

### 3. When You Get Stuck
1. Re-read the instructions carefully
2. Check AWS/tool documentation
3. Search the error message
4. Ask in community (Slack, Reddit, Stack Overflow)
5. Document the solution for others

### 4. Manage AWS Costs
```bash
# Check costs daily
aws ce get-cost-and-usage \
    --time-period Start=2025-02-01,End=2025-02-10 \
    --granularity DAILY \
    --metrics "UnblendedCost"

# Clean up weekly
terraform destroy  # When done with resources
aws ec2 describe-instances  # Check for running instances
```

### 5. Time Management
- Block calendar for study time
- Use Pomodoro (25 min work, 5 min break)
- Weekend deep dives (4-6 hours)
- Don't burn out - rest is important

## 🔄 Weekly Cycle

### Monday
- Review previous week retrospective
- Read new week's README
- Set up environment for new tools
- Start Day 1 exercises

### Tuesday-Thursday
- Follow daily guides
- Commit code
- Document learnings
- Stay consistent

### Friday
- Complete week's deliverables
- Write retrospective
- Update main README
- Plan weekend work

### Saturday
- Deep dive into complex topics
- Build larger projects
- Catch up if behind
- Practice hands-on

### Sunday
- Review entire week
- Prepare for next week
- Rest and recharge
- Update portfolio

## 📊 Deliverables Checklist

### Each Week Should Produce:
- [ ] Working code/configurations
- [ ] Documentation (markdown files)
- [ ] Screenshots of dashboards/results
- [ ] Lessons learned document
- [ ] Updated README with progress
- [ ] Git commits (minimum 5-7 per week)

### End of Program (Week 8):
- [ ] Complete portfolio on GitHub
- [ ] All 8 weeks documented
- [ ] Capstone project deployed
- [ ] Architecture diagrams
- [ ] Presentation-ready materials
- [ ] LinkedIn profile updated
- [ ] Resume updated

## 🎓 Certification Track

### Parallel to Learning
While going through weeks, also:
1. **Read AWS whitepapers** (15 min/day)
2. **Watch AWS re:Invent videos** (relevant talks)
3. **Review service FAQs** (each service you use)
4. **Practice questions** (start Week 4)

### Week 7-8 Focus
- Take practice exams
- Review weak areas
- Hands-on with exam services
- Schedule certification

## 📞 Getting Help

### When to Ask for Help
- After 30 minutes stuck on same error
- Before spending money (verify first)
- When unsure about security implications
- Before deleting something important

### Where to Get Help
1. **GitHub Issues** - Create issue in your own repo
2. **AWS Forums** - forum.aws.com
3. **Reddit** - r/aws, r/kubernetes, r/devops
4. **Slack Communities** - DevSecOps communities
5. **Stack Overflow** - Tag questions properly

### How to Ask Good Questions
```
Bad: "Terraform doesn't work, help!"

Good: 
"Getting error when applying Terraform CloudTrail config:

Error: Access Denied when creating S3 bucket policy

Environment:
- Terraform v1.6.0
- AWS CLI v2.13
- Profile: admin (verified with `aws sts get-caller-identity`)

What I tried:
- Verified S3 bucket exists
- Checked IAM permissions (have PutBucketPolicy)
- Reviewed CloudTrail docs

Code: [paste relevant code]
Output: [paste full error]
```

## 🚀 Ready to Start?

### Pre-flight Checklist
- [ ] Repository forked and cloned
- [ ] AWS account created
- [ ] AWS CLI configured
- [ ] All tools installed (see QUICK_START.md)
- [ ] Calendar blocked for study time
- [ ] Notebook/documentation tool ready
- [ ] Excited and motivated! 🎯

### First Command
```bash
cd cloud-security-upskill-portfolio/week-01-aws-security
cat README.md
```

### Good Luck! 🍀

Remember:
- **Quality over speed** - Better to master one week than rush through all
- **Document everything** - Your future self will thank you
- **Ask questions** - Community is here to help  
- **Build in public** - Share your progress
- **Stay consistent** - 20 hours/week beats 40 hours one week then nothing

---

**You're about to gain skills that are in high demand. Let's go! 🚀**

## ❓ FAQ

**Q: What if I can't finish in 8 weeks?**
A: Extend the timeline. Quality learning > arbitrary deadlines.

**Q: Should I delete AWS resources after each week?**
A: Yes, to save costs. Keep code, destroy infrastructure.

**Q: Can I skip weeks?**
A: Not recommended. Each builds on previous weeks.

**Q: What if I already know some topics?**
A: Skim theory, focus on hands-on practice and documentation.

**Q: How do I showcase this in interviews?**
A: "Let me walk you through my GitHub portfolio..." [Share screen]

**Q: After 8 weeks, then what?**
A: CKS certification, contribute to open source, apply for jobs!

---

**Document Version**: 1.0  
**Last Updated**: February 2025

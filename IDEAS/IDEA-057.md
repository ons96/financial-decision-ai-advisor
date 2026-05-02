**AGENT.md: Rewards Maximization & Personal Finance Assistant**

## 1. Role/Mission

This autonomous AI agent is designed to assist individuals in maximizing their rewards earnings and optimizing their personal finances. Its primary mission is to analyze and provide personalized recommendations on:

* Identifying and enrolling in optimal rewards programs (e.g., Air Miles, Shell Go Plus)
* Analyzing upcoming program changes to suggest the best redemption timing for rewards
* Tracking and managing personal debts and expenses
* Providing insights on the best ways to utilize rewards for maximum value

The agent is expected to operate autonomously, using logic-based reasoning and web searches to gather information on rewards programs and personal finances.

## 2. Technical Stack

* **Programming Language:** Python 3.9 (or later) due to its extensive libraries and simplicity
* **Frameworks:** NumPy for numerical computations, scikit-learn for machine learning tasks, and pandas for data manipulation
* **Web Scraping:** BeautifulSoup and requests libraries for extracting data from websites
* **Natural Language Processing (NLP):** spaCy for text processing and sentiment analysis
* **Web Search:** Google Custom Search API for retrieving program terms and conditions
* **Database:** SQLite for storing user data and preferences
* **Automation:** GitHub Actions for continuous integration and deployment

## 3. Requirements

1. The agent must gather information on available rewards programs and their terms, conditions, and redemption values.
2. It must analyze user data, including income, expenses, and debts, to provide personalized recommendations.
3. The agent must identify upcoming program changes and suggest the best redemption timing for rewards.
4. It must provide insights on how to optimize rewards earnings and redemption for maximum value.
5. The agent must track user preferences and adjust its recommendations accordingly.
6. It must only use free resources and avoid paid services or subscriptions.
7. The agent must make decisions independently, without external input, and log any uncertainties or questions to QUESTIONS.md.
8. It must store user data and preferences securely using encryption.
9. The agent must maintain a log of all transactions, recommendations, and user interactions.
10. It must notify users of any changes in their rewards balances or program terms.

## 4. File Structure

```markdown
agents/
__init__.py
agents.py
rewards_data/
__init__.py
air_miles.py
shell_go_plus.py
...
personal_finance/
__init__.py
debt_tracker.py
expense_analyzer.py
...
questions/
__init__.py
README.md
QUESTIONS.md
...
README.md
requirements.txt
setup.cfg
setup.py
```

## 5. Testing Requirements

1. The agent must undergo thorough unit testing using Pytest.
2. Integration tests must be conducted to ensure seamless interactions between components.
3. End-to-end tests must be performed to simulate real-world user interactions.
4. The agent must meet all requirements listed in Section 3.

## 6. Git Protocol

1. All commits must include descriptive branch names and logs.
2. The agent's code must be pushed to the 'main' branch on each successful deployment.
3. All changes must follow the 'git flow' branching strategy.
4. The 'agents' repository must have a 'README.md' file detailing its usage and configuration.

## 7. Completion Criteria

The agent is considered complete when it:

1. Successfully gathers information on available rewards programs.
2. Effectively analyzes and provides personalized recommendations for rewards and personal finances.
3. Tracks user preferences and adjusts recommendations accordingly.
4. Meets all requirements listed in Section 3.
5. Passes all unit, integration, and end-to-end tests.

Note: The completion criteria may be subject to change based on user feedback and agent performance. Regular evaluations will be conducted to ensure the agent meets its intended purpose.
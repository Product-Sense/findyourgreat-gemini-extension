# FindYourGreat for Gemini CLI

Access your [FindYourGreat](https://www.findyourgreat.com) work data directly from Gemini CLI. Query your work activity, career evaluation scores, behavioral patterns, development plans, impact updates, and team information through 39 read-only tools.

## Install

```bash
gemini extensions install https://github.com/brendanfortune/findyourgreat-gemini-extension
```

## Authentication

On first use, Gemini CLI will open your browser for OAuth authentication. Sign in with your FindYourGreat account, pick your organization, and approve the requested scopes. Tokens are stored locally and refreshed automatically.

## Available tools

| Scope | Tools | Description |
|---|---|---|
| Work activity | `list_activities`, `get_activity_detail`, `list_projects`, `get_project_detail`, `list_decisions`, `get_decision_detail`, `list_meetings`, `get_meeting_detail`, `get_meeting_feedback`, `search_meeting_transcript` | Slack messages, GitHub PRs, Linear issues, meeting transcripts, decisions |
| Career signals | `list_episodes`, `get_episode_detail`, `list_evaluations`, `get_evaluation_detail`, `get_member_scores`, `get_score_history` | Career episodes, evaluation scores, score trends |
| Patterns | `list_greats`, `get_great_detail` | Behavioral patterns and supporting evidence |
| Plans & goals | `list_plans`, `get_plan_detail`, `list_team_goals`, `get_team_goal_detail`, `list_value_barriers` | Development plans, team goals, value barriers |
| Impact | `list_impact_feed`, `get_impact_feed_detail`, `list_impact_feed_setup`, `get_impact_summary`, `get_impact_model`, `get_impact_stats`, `get_value_barrier_detail`, `get_what_you_do_summary` | Impact updates, impact models, contribution summaries |
| Team | `list_members`, `get_member_detail`, `list_teams`, `get_team_detail`, `get_member_impact_chain` | Team members, org structure, impact chains |

## Example prompts

- "List my 5 most recent work activities"
- "How are my evaluation scores trending over the past 3 months?"
- "What are my top behavioral patterns?"
- "Give me a summary of my week — projects, decisions, and meetings"

## Links

- [FindYourGreat](https://www.findyourgreat.com)
- [Privacy Policy](https://www.findyourgreat.com/privacy)
- [Terms of Service](https://www.findyourgreat.com/terms)

# Claude-Skills
Claude에서 사용하기 위한 Skills.

Skill 사용 방법

**[ Claude Desktop ]**
 - Setting > Skills에서 스킬 파일 업로드
   (SKILL.md 파일이 포함된 zip파일)

**[ Claude Code ]**
#### Personal Skills로 설치 (모든 프로젝트에서 사용)
(~/.claude/skills/{my-skills}/SKILL.md)  
- cd ~/.claude/skills/
- unzip /path/to/weeds-meeting.skill

#### Project Skills로 설치 (현재 프로젝트만)
(/project/.claude/skills/{my-skills}/SKILL.md)
- cd /your/project/.claude/skills/
- unzip /path/to/weeds-meeting.skill

설치 후 구조:  
~/.claude/skills/  
└── weeds-meeting/  
────├── SKILL.md  
────└── references/  
───────├── meeting_format.md  
───────└── examples.md  

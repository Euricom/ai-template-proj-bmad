# ai-template-proj-bmad

Vol de stappen je brain-dump klaar te maken.

## 1. Installeer Obsidian
Obsidian is een note taking app gebaseerd op markdown

Open, download & install
https://obsidian.md/download

## 2. Installeer NodeJS
NodeJS is een JS runtime waar je JavaScript applicaties (NodeRed & Claude) mee kan draaien.

Open & download & macOS installer
https://nodejs.org/en/download/

## 3. Installeer Warp 
Warp is een meer geavanceerde terminal window met AI powers. Claude is een terminal applicatie en Warp is een makkelijke manier om deze op te starten.

Open, download and install
https://www.warp.dev/

## 4. Installeer Claude Code & dependencies

### MacOS

Open Warp en

```bash
# Run following command
npm install -g @anthropic-ai/claude-code

# Configure API key
echo 'export ANTHROPIC_API_KEY="your-secret-key" >> ~/.zshrc`
```

### Windows 

Open Warp en

```bash
# Open the terminal (Warp) as administrator
# Run the following command
$ Set-ExecutionPolicy RemoteSigned

# Close your terminal and re-open as normal user
npm install -g @anthropic-ai/claude-code

# Configure API key in your environment variables
#   Launch "Control Panel", "System", "Advanced system settings", Switch to "Advanced" tab
#   Open "Environment variables", Choose "System Variables" (for all users)
#   Add a new environment variable: ANTHROPIC_API_KEY

# Install Git for windows 
#   https://git-scm.com/install/windows
```

## 6. Start een BMAD brainstorm 

Volg de stappen om een brainstorm te starten

1. Open Warp op je application folder
2. Start Claude
   
```
$ claude
╭───────────────────────────────────────────────────╮
│ ✻ Welcome to Claude Code!                         │
│                                                   │
│   /help for help, /status for your current setup  │
│                                                   │
│   cwd: /Users/peter/git/temp/jasper/brain-dump    │
│                                                   │
│   ─────────────────────────────────────────────── │
│                                                   │
│   Overrides (via env):                            │
│                                                   │
│   • API Key: sk-ant-…bacOFP7HJLNXpGb_kFw-JNADuwAA │
╰───────────────────────────────────────────────────╯
```

3. Start de `analyst`
```
/analyst

Ik ben gespecialiseerd in marktonderzoek, brainstormen, concurrentieanalyse, projectbriefs, en initiële projectontdekking. Als strategisch analist help ik je met onderzoek, ideeën ontwikkelen en actionable inzichten creëren.    
```

# jarvis

## Jarvis utilizes doskey to make several commands in windows friendly to common user

### Current commands
- "c" = cls :: clears screen
- "gits" = git status
- "gitc" = git commit
- "giti" = git init
- "gb" = gradle build
- "gcb" = gradle clean build
- "gr" = gradle run
- "gc" = gradle clean
- "what" = echo gits = git status gitc = git commit giti = git init gb = gradle build gr = gradle run gc = gradle clean
- "hi" = echo hello
- "bye" = exit

## Run
To run jarvis you will need to replace a cmd shortcut with:
```
	%windir%\system32\cmd.exe /K C:\Users\Your_User\jarvis\cmd-jarvis.bat
```

## _*WARNING*_
If you choose to add custom commands you are responsible for their outcome

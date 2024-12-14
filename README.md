# Cheats [v3]
### Cheats for Entropy Linux, a community driven, shell alias interpreter.
> **Enter cheat codes to execute predefined commands** \
> All commands can be found in `data.json` \
*(Inspired by cheat codes in retro games)*
> ### Upsides:
+ Each new cheat adds entire 0b of bloat to each system
+ Easy to update and manage remotely as json files on GitHub
+ Great way to add semi-official features to distro
+ Easy to remember aliases are good for accesibility
---

## Cheats now support multiple `data.json` files from any source you wish!
> Add your own cheats, by hosting your own repo with `data.json`, and adding
> `"repo-name": "<URL>"` to REPOSITORIES like
```bash
REPOSITORIES='{
  "default": "https://raw.githubusercontent.com/Szmelc-INC/Cheats/refs/heads/main/data.json",
  "repo-xyz": "https://raw.githubusercontent.com/xyz/data.json"
}'
```
> Then run cheats with optional flag `--data` to specify repo to use, like \
> `cheats -d repo-xyz`

#### Flags!
> Cheats now support optional --flags, like `-d --data`, `-l --list`, and `-h --help`


---

# How To Contribute
> To submit your own cheats, please use provided form on cheats explorer page, or use this form
```
Cheat Code:
<CODE>

Command:
<COMMAND>

Description:
<DESCRIPTION>
```
And send it to `szmelcinc@gmail.com`, in message titled `New Cheat Submission`

**EXAMPLE**
```
Cheat Code:
Rickroll

Command:
nohup mpv https://www.youtube.com/watch?v=dQw4w9WgXcQ & 

Description:
Play Rick in terminal via MPV!
```


# Screenshots
### Cheats v3
![image](https://github.com/user-attachments/assets/21a020bc-0f98-4a02-93a2-7df43ae8daf9)

### Built in #list command
![image](https://github.com/user-attachments/assets/09843b24-5e9d-48de-a444-86ca08000b49)

### `cheats --list` command
![image](https://github.com/user-attachments/assets/40814740-b29e-48ac-8612-7077c01aa3b1)

# [Entropy Cheats Explorer](https://entropy-linux.github.io/cheats/)
> ### Browse & submit cheats website
<img src="https://github.com/user-attachments/assets/71b12ccc-2764-4970-9984-ba86850c5f10" style="width: 50%; height: auto;" alt="Image">

---


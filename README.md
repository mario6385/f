# Among us 4: new 9 roles

**version 1 roles:**<br/>
- [Medic](#medic)
- [Sheriff](#sheriff)
- [Engineer](#engineer) 
- [Cat](#cat) 
- [Jester](#jester) 
- [Survivor](#survivor) 
- [Janitor](#Janitor) 
- [Morphling](#morphling) 
- [Blackmailer](#blackmailer) 

-----------------------
# Roles
## Medic
### **Team: Crewmate**
The Medic is a Crewmate who can give 1 player a shield that will make them immortal until the Medic dies. A Shielded player cannot be Shifted into, Hacked or Killed by anyone, unless by suicide. They can also revive a dead body. If the Medic reports a dead body, they can get a report containing clues to the Killer's identity. A report can contain the name of the killer or the color type (Darker/Lighter).

### Game Options
| Name | Description | range | Default |
|----------|:-------------:|:------:|:------:|
| Medic | The percentage probability of the Medic appearing | 0%~100% | 0% |
| Show Shielded Player | Who should be able to see who is Shielded | Self / Medic / Self + Medic / Everyone | Self |
| Show Medic Reports | Whether the Medic gets information when reporting a body | True/False | True |
| Time Where Medic Reports Will Have Name | If a body has been dead for shorter than this amount, the Medic's report will contain the killer's name | Time | 0s |
| Time Where Medic Reports Will Have Color Type | If a body has been dead for shorter than this amount, the Medic's report will have the type of color | 10s~60s | 15s |
| Who gets murder attempt indicator | Who will receive an indicator when someone tries to Shift into, Hack or Kill them | Medic / Shielded / Everyone / Nobody | Medic |
| Shield breaks on murder attempt | Whether the Shield breaks when someone attempts to Shift into, Hack or Kill them | True/False | False |
| Revive cooldown | The Cooldown of reviving | 5s~60s | 10s |

-----------------------
## Sheriff
### **Team: Crewmate**
The Sheriff is a Crewmate who can kill the Impostors. However, if they kill a Crewmate or a Neutral player they can't kill, they instead die themselves.

### Game Options
| Name | Description | range | Default |
|----------|:-------------:|:------:|:------:|
| Sheriff | The percentage probability of the Sheriff appearing | 0%~100% | 0% |
| Show Sheriff | Whether everybody can see who the Sheriff is | True/False | False |
| Sheriff Miskill Kills Crewmate | Whether the other player is killed if the Sheriff Misfires | True/False | False |
| Sheriff Kills Jester | Whether the Sheriff is able to kill the Jester | True/False | False |
| Sheriff Kills serial killer | Whether the Sheriff is able to kill serial killer | True/False | False |
| Sheriff Kills Arsonist | Whether the Sheriff is able to kill the Arsonist | True/False | False |
| Sheriff Kills plague bearer | Whether the Sheriff is able to kill the plague bearer | True/False | False |
| Sheriff Kill Cooldown | The cooldown of Sheriff's killing | 10~60s | 25s |
| Sheriff can report who they've killed | Whether the Sheriff is able to report their own kills | True/False | True |

-----------------------
## Engineer
### **Team: Crewmate**
The Engineer is a Crewmate who can fix sabotages easily, and fix sabotages in anywhere. They can use vents to get across the map easily.

### Game Options
| Name | Description | range | Default |
|----------|:-------------:|:------:|:------:|
| Engineer | The percentage probability of the Engineer appearing | 0%~100% | 0% |
| Engineer Fix Per | Whether the Engineer can fix 1 sabotage per round or per game | None / Round / Game | Round |
| Sheriff Kill Cooldown | The cooldown of Engineer's fixing sabotage | 10~60s | 25s |

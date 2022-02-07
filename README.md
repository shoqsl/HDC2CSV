# HDC2CSV
Convert HERO Builder .hdc files into .csv files

Hero Object - Stores information on One Hero
    Strings:
        Hero Name
    Integers:
        Character Points
        Experience Points
        Total Points

        Points in:
            Characteristics
            Skills
            Perks
            Talents
            Martial Arts
            Powers

        Characteristic Points:
            STR
            DEX
            CON
            INT
            EGO
            PRE
            OCV
            DCV
            MOCV
            MDCV
            SPD
            PD
            ED
            REC
            END
            BODY
            STUN
            Run
            Swim
            Leap

    Objects:
        Specific Skills: [Skill Name (String) - Skill Characteristic (String) - Value (Integer)]
            Acrobatics
            Acting
            *Analyze
            Animal Handler
            Autofire Skills
            Breakfall
            Bribery
            Bugging
            Bureaucratics
            Charm
            Climbing
            Combat Driving
            Combat Piloting
            Combat Skill Levels
            Computer Programming
            Concealment
            Contortionist
            Conversation
            Cramming
            Criminology
            Cryptography
            *Custom Skill
            Deduction
            Defense Maneuver
            Demolitions
            Disguise
            Electronics
            Fast Draw
            Forensic Medicine
            Forgery
            Gambling
            High Society
            Interrogation
            Inventor
            *Knowledge Skill
            Language
            Lipreading
            Lockpicking
            Mechanics
            *Mental Combat Skill Levels
            Mimicry
            Navigation
            Oratory
            Paramedics
            *Penalty Skill Levels
            Persuasion
            *Power
            *Professional Skill
            Rapid Attack
            Riding
            *Science Skill
            Security Systems
            Shadowing
            *Skill Levels
            Sleight of Hand
            Stealth
            Streetwise
            Survival
            Systems Operation
            Tactics
            Teamwork
            Tracking
            Trading
            Transport Familiarity
            Two-Weapon Fighting
            Ventriloquism
            Weapon Familiarity
            Weaponsmith

            Wildcard skills
                Analyze
                Custom Skill
                Knowledge(KS)
                Language
                Professional
                Science(SS)
                Skill Levels

Tables:
    Point Spread Table:
        |Total spent points | Character Full Name | Characteristics (w/%) | Skills (w/%) | Perks (w/%) | Talents (w/%) | Martial Arts (w/%) | Powers (w/%) |

    Characteristics Table:
        |      | Character n | Character n+1 |
        | STR  |
        | DEX  |
        | CON  |
        | INT  |
        | EGO  |
        | PRE  |
        |      |
        | OCV  |
        | DCV  |
        | MOCV |
        | MDCV |
        | SPD  |
        |      |
        | PD   |
        | ED   |
        | REC  |
        | END  |
        | BODY |
        | STUN |
        |      |
        | Run  |
        | Swim |
        | Leap |

    Skills Table:
        |                |            |                      | Character n | Character n+1 |
        | Skill Category |            |                      |             |               |
        |                | Skill Name | Skill Characteristic | Value       | Value         |

        Skill Categories are derived from Wildcard Skills and may have Variable Names
# Command Chosen: less
## Command-Line Option 1: -N
Example 1:  
Input:  
```
less -N technical/biomed/1468-6708-3-1.txt
```  
Output(Only shows part of the output to save space):  
```
      1 
      2   
      3     
      4       
      5         Introduction
      6         Older adults are frequently counseled to lose weight,
      7         even though there is little evidence that overweight is
      8         associated with increased mortality in those over age 65.
      9         Six large controlled population-based studies of
     10         non-smoking older adults have investigated the association
     11         between body mass index (BMI) and mortality, controlling
     12         for relevant covariates [ 1 2 3 4 5 6 ] . All studies found
     13         excess risk for persons with very low BMI, but that persons
     14         with moderately high BMI had little or no extra risk except
     15         in certain small subsets. A review of 13 studies of older
     16         adults drew similar conclusions [ 7 ] .
     17         Many healthy older adults report gradual weight gain
     18         throughout adult life. It may be that a small amount of
     19         gradual weight gain is normative and associated with the
     20         most robust health as we age. It has been suggested that
     21         weight standards be adjusted upwards for age [ 8 ] . Such
     22         recommendations remain controversial, however, because the
     23         number of studies of older persons is fairly small, and
     24         because few studies have examined the relation of BMI to
     25         quality of life or years of healthy life (YHL) in the
     26         elderly [ 9 ] .
```
This command shows the contents of the file, along with the numbered lines. This can be helpful for reviewing long files such as this one, since it can be easier to keep track of the lines.  
Example 2:  
Input:  
```
less -N technical/911report/chapter-1.txt
```  
Output(Only shows part of the output to save space):  
```
 1 
      2         
      3                 
      4 "WE HAVE SOME PLANES"
      5 
      6     Tuesday, September 11, 2001, dawned temperate and nearly cloudless in the eastern United States. Millions of men and women readie
      6 d themselves for work. Some made their way to the Twin Towers, the signature structures of the World Trade Center complex in New York
      6  City. Others went to Arlington, Virginia, to the Pentagon. Across the Potomac River, the United States Congress was back in session.
      6  At the other end of Pennsylvania Avenue, people began to line up for a White House tour. In Sarasota, Florida, President George W. B
      6 ush went for an early morning run.
      7 
      8     For those heading to an airport, weather conditions could not have been better for a safe and pleasant journey. Among the travele
      8 rs were Mohamed Atta and Abdul Aziz al Omari, who arrived at the airport in Portland, Maine.
      9 
     10 INSIDE THE FOUR FLIGHTS
     11 
     12 Boarding the Flights
     13 
     14     Boston: American 11 and United 175. Atta and Omari boarded a 6:00 A.M. flight from Portland to Boston's Logan International Airpo
     14 rt.
     15 
     16     When he checked in for his flight to Boston, Atta was selected by a computerized prescreening system known as CAPPS (Computer Ass
     16 isted Passenger Prescreening System), created to identify passengers who should be subject to special security measures. Under securi
     16 ty rules in place at the time, the only consequence of Atta's selection by CAPPS was that his checked bags were held off the plane un
     16 til it was confirmed that he had boarded the aircraft. This did not hinder Atta's plans.
     17 
     18     Atta and Omari arrived in Boston at 6:45. Seven minutes later, Atta apparently took a call from Marwan al Shehhi, a longtime coll
     18 eague who was at another terminal at Logan Airport. They spoke for three minutes.
     19 
     20     It would be their final conversation.
     21 
     22     Between 6:45 and 7:40, Atta and Omari, along with Satam al Suqami, Wail al Shehri, and Waleed al Shehri, checked in and boarded A
     22 merican Airlines Flight 11, bound for Los Angeles. The flight was scheduled to depart at 7:45.
     23 
     24     In another Logan terminal, Shehhi, joined by Fayez Banihammad, Mohand al Shehri, Ahmed al Ghamdi, and Hamza al Ghamdi, checked in
     24  for United Airlines Flight 175, also bound for Los Angeles. A couple of Shehhi's colleagues were obviously unused to travel; accordi
     24 ng to the United ticket agent, they had trouble understanding the standard security questions, and she had to go over them slowly unt
     24 il they gave the routine, reassuring answers.
     25 
     26     Their flight was scheduled to depart at 8:00.
```  
This command shows the contents inside the file with the line numbers on the side. This command is useful because in this file, there are paragraphs that have the same line numbers, which indicates that the contents have been written on the same line, just moved down.  
  
Command-line option found on:  
[https://phoenixnap.com](https://phoenixnap.com/kb/less-command-in-linux)  
## Command-Line Option 2: -X  
Example 1:  
Input:  
```
less -X technical/government/Alcohol_Problems/DraftRecom-PDF.txt
```
Output:  
```
Discussion of
Draft Recommendations

Daniel Hungerford opened the final session of the conference by
outlining the group's ultimate task-to create research
recommendations from conference deliberations. Before the
conference, he and Daniel Pollock drafted recommendations for the
steering committee to consider. During the conference, the steering
committee modified those recommendations, and they were distributed
to attendees for general discussion.
Hungerford stated that the goal of the conference was not to
achieve unanimity regarding the recommendations, but to have
significant and general agreement. He indicated the process would
be to discuss the recommendations one by one, identifying any gaps
or omissions and offering general comments. He emphasized that the
sequence of the recommendations did not imply a priority order.
Because the published recommendations will include supporting text,
he encouraged the group to consider any points of clarification
that would be instructive. Hungerford then opened the floor for
discussion.
Recommendation #1 Research on screening and intervention should
address the full spectrum of alcohol problems among ED
patients.
Richard Brown remarked that in many circles, "intervention" does
not necessarily include referral, so he suggested that the first
recommendation include "referral." Also, he said the phrase
"alcohol problems" does not always include risky drinking and
problem drinking, so he suggested adding "risky and problem
drinking" to the recommendation.
Daniel Hungerford noted that the supporting text could provide
detail on the spectrum of alcohol problems. He suggested the main
point of the first recommendation was that research efforts should
include the whole continuum of alcohol problems, not just a portion
of the continuum such as alcohol-dependent drinkers.
Jean Shope advocated that the definition of "the full spectrum
of alcohol problems" include primary prevention. She recommended
this under-standing be made explicit in the final document.
Gordon Smith suggested that the recommendations should address
the problems of poly-substance abuse.
Carl Soderstrom wondered whether "alcohol problems" referred to
the spectrum of drinking problems or the medical problems
associated with drinking.
Herman Diesenhaus pointed out that hazardous drinking causes a
Jordans-MacBook-Air-2:docsearch jordan35chang$
```
In this command, it still gives the contents of the file as the output, however, now when exiting the file the contents stay in the terminal. This can be useful to compare changes in the files after commands are run to see if they work properly.  
Example 2:  
Input:  
```
less -X technical/plos/pmed.0020274.txt
```
Output:  
```
        The World Health Organization estimates that about 20% of all deaths in children younger
        than five years old are due to acute lower respiratory tract infections (LRTIs), with 90%
        of these deaths due to pneumonia. But despite LRTIs being among the most frequent diseases
        in the first years of life, the viral causes of these illnesses are not always clear.
        Several viruses are known to be involved, e.g., respiratory syncytial virus (RSV),
        influenza viruses, parainfluenza viruses, and human metapneumovirus, but none of these
        pathogens is detected in a substantial number of cases.
        In a new article published in 
        PLoS Medicine , Lia van der Hoek and colleagues investigate the
        association of acute LRTIs with human coronavirus HCoV-NL63, a virus they recently
        described. They suggest that HCoV-NL63, a new member of the Coronaviridae family, is one of
Jordans-MacBook-Air-2:docsearch jordan35chang$ 
```
This command gives the contents of the file, and keeps them even after exiting the command. This can be useful for when you need to reuse certain aspects of a file in another one, since then you wouldn't have to directly open the other file.

Command-Line Option found on:  
[https://linuxize.com](https://linuxize.com/post/less-command-in-linux/)  
## Command-Line Option 3: -s
Example 1:  
Input:  
```
less -s technical/biomed/1468-6708-3-1.txt
```  
Output:
```
 Introduction
        Older adults are frequently counseled to lose weight,
        even though there is little evidence that overweight is
        associated with increased mortality in those over age 65.
        Six large controlled population-based studies of
        non-smoking older adults have investigated the association
        between body mass index (BMI) and mortality, controlling
        for relevant covariates [ 1 2 3 4 5 6 ] . All studies found
        excess risk for persons with very low BMI, but that persons
        with moderately high BMI had little or no extra risk except
        in certain small subsets. A review of 13 studies of older
        adults drew similar conclusions [ 7 ] .
        Many healthy older adults report gradual weight gain
        throughout adult life. It may be that a small amount of
        gradual weight gain is normative and associated with the
        most robust health as we age. It has been suggested that
        weight standards be adjusted upwards for age [ 8 ] . Such
        recommendations remain controversial, however, because the
        number of studies of older persons is fairly small, and
        because few studies have examined the relation of BMI to
        quality of life or years of healthy life (YHL) in the
        elderly [ 9 ] .
        In older adults, risk factors may have a greater effect
        on health than on mortality. If so, then behavior change
        trials of weight modification might be more successful if
        they were evaluated on improved health, rather than on
        decreased mortality. Clinical trials powered to detect
        differences in YHL would often require fewer subjects than
        trials to detect survival differences or cardiovascular
        events [ 10 ] . In this paper we study whether BMI at
        baseline is associated with living longer, and/or with more
        years of being healthy, in a cohort of older adults for
        whom risk factors, subclinical disease, and morbidity are
        well characterized. The goal is to determine whether
        analyses based on years of life (YOL) or on YHL would
        provide substantively different results, and which measure
        would yield more powerful evaluations of weight
        modification interventions in older adults.
      
      
        Materials and methods
        
          Study design: The Cardiovascular Health
          Study
          The Cardiovascular Health Study (CHS) is a
          population-based longitudinal study of 5,888 adults aged
          65 and older at baseline [ 11 ] . Subjects were recruited
```  
This command gives back the contents of the file combines consecutive blank lines into one blank line. This can be useful for saving memory when trying to view a file.  
Example 2:  
Input:  
```
less -s technical/government/Env_Prot_Agen/bill.txt
```  
Output:  
```
''Sec. 441. Nitrogen Oxides Emission Reduction Program ''Sec.
442. Termination.
''Subpart 2-Nitrogen Oxides Allowance Program
''Sec. 451. Definitions. ''Sec. 452. Applicability. "Sec. 453.
Limitations on total emissions. ''Sec. 454. Allocations.
''Subpart 3-Ozone Season NOx Budget Program
''Sec. 461. Definitions. ''Sec. 462. General Provisions. "Sec.
463. Applicable Implementation Plan. ''Sec. 464. Termination of
Federal Administration of NOx Trading Program. "Sec. 465.
Carryforward of Pre-2008 Nitrogen Oxides Allowances.
''PART D-MERCURY EMISSION REDUCTIONS
''Sec. 471. Definitions. ''Sec. 472. Applicability. "Sec. 473.
Limitations on total emissions. ''Sec. 474. Allocations.
''PART E-NATIONAL EMISSION STANDARDS; RESEARCH; ENVIRONMENTAL
ACCOUNTABILITY; MAJOR SOURCE PRECONSTRUCTION REVIEW AND BEST
AVAILABLE RETROFIT CONTROL TECHNOLOGY REQUIREMENTS.
''Sec. 481. National emission standards for affected units.
''Sec. 482. Research, environmental monitoring, and assessment.
''Sec. 483. Major source preconstruction review and best
availability retrofit control technology requirements."
Sec. 3. Other amendments.

SEC. 2. EMISSION REDUCTION PROGRAMS.
Title IV of the Clean Air Act (relating to acid deposition
control) (42 U.S.C. 7651, et seq.) is amended to read as
follows:
''TITLE IV- EMISSION REDUCTION PROGRAMS
PART A. GENERAL PROVISIONS.
SEC. 401. (Reserved)
SEC. 402. DEFINITIONS.
As used in this title-

(1)
The term "affected EGU" shall have the meaning set forth
in section 421, 431, 451, or 471,as appropriate.

(2)
The term "affected facility" or "affected source" means a
facility or source that includes oneor more affected
units.

(3)
The term "affected unit" means-

(A)
Under this part, a unit that is subject to emission
reduction requirements orlimitations under part B, C, or D or, if
:
```  
This command combines multiple blank lines in the contents of a file into one blank line. This can be useful for viewing long files like this, since it compacts the files contents.  
Command-Line Option found on:  
[https://man7.org](https://man7.org/linux/man-pages/man1/less.1.html)
## Command-Line Option 4: -e
Example 1:  
Input:  
```
less -e technical/911report/chapter-6.txt
```  
Output:  
```
 FROM THREAT TO THREAT
            In chapters 3 and 4 we described how the U.S. government adjusted its existing
                agencies and capacities to address the emerging threat from Usama Bin Ladin and his
                associates. After the August 1998 bombings of the American embassies in Kenya and
                Tanzania, President Bill Clinton and his chief aides explored ways of getting Bin
                Ladin expelled from Afghanistan or possibly capturing or even killing him. Although
                disruption efforts around the world had achieved some successes, the core of Bin
                Ladin's organization remained intact. President Clinton was deeply concerned about
                Bin Ladin. He and his national security advisor, Samuel "Sandy" Berger, ensured they
                had a special daily pipeline of reports feeding them the latest updates on Bin
                Ladin's reported location.
            
            In public, President Clinton spoke repeatedly about the threat of terrorism,
                referring to terrorist training camps but saying little about Bin Ladin and nothing
                about al Qaeda. He explained to us that this was deliberate-intended to avoid
                enhancing Bin Ladin's stature by giving him unnecessary publicity. His speeches
                focused especially on the danger of nonstate actors and of chemical and biological
                    weapons.
            
            As the millennium approached, the most publicized worries were not about terrorism
                but about computer breakdowns-the Y2K scare. Some government officials were
                concerned that terrorists would take advantage of such breakdowns.
            
            THE MILLENNIUM CRISIS
            "Bodies Will Pile Up in Sacks"
            On November 30, 1999, Jordanian intelligence intercepted a telephone call between Abu
                Zubaydah, a longtime ally of Bin Ladin, and Khadr Abu Hoshar, a Palestinian
                extremist. Abu Zubaydah said, "The time for training is over." Suspecting that this
                was a signal for Abu Hoshar to commence a terrorist operation, Jordanian police
                arrested Abu Hoshar and 15 others and informed Washington.
            
            One of the 16, Raed Hijazi, had been born in California to Palestinian parents; after
                spending his childhood in the Middle East, he had returned to northern California,
                taken refuge in extremist Islamist beliefs, and then made his way to Abu Zubaydah's
                Khaldan camp in Afghanistan, where he learned the fundamentals of guerrilla warfare.
                He and his younger brother had been recruited by Abu Hoshar into a loosely knit plot
                to attack Jewish and American targets in Jordan.
            
            After late 1996, when Abu Hoshar was arrested and jailed, Hijazi moved back to the
                United States, worked as a cabdriver in Boston, and sent money back to his fellow
                plotters. After Abu Hoshar's release, Hijazi shuttled between Boston and Jordan
                gathering money and supplies. With Abu Hoshar, he recruited inTurkey and Syria as
                well as Jordan; with Abu Zubaydah's assistance, Abu Hoshar sent these recruits to
                Afghanistan for training.
```
This command exits the file contents when the end of the file is reached. This can be useful for exiting the file easier without having to input any command.  
Example 2:  
Input:  
```
less -e technical/government/Media/AP_LawSchoolDebts.txt
```  
Output:  
```
The Associated Press

Law school debts forcing recruits to private sector
November 18, 2002
WASHINGTON (AP) - Most new lawyers won't consider working for
government or public advocacy groups because their need for money
to pay off massive student loans leads them to the more lucrative
private sector, a study being released Monday found.
Legal education debt, which tops $84,000 for the average new
lawyer, prevents 66 percent of law students from taking public
interest jobs, according to the joint study by Equal Justice Works,
the National Association for Law Placement and the Partnership for
Public Service. The Washingtonbased groups promote public interest
work.
"The bottom line is America's law school graduates are drowning
in debt and shut out of public service at a time when the federal
government is facing losses of over half its work force due to
retirements," said Max Stier, president and chief executive of the
Partnership for Public Service.
More than 94 percent of law students reported borrowing money to
attend law school, where median tuition is nearly $23,000 a year,
but law students are not alone in having to contend with spiraling
education costs.
The need to pay off student loans discourages doctors from going
to rural communities or inner-city hospitals. A chronic teacher
shortage has led some states to consider ways to help
teaching-educa-tion students pay off college debts.
The student loan agency Nellie Mae says the average college
graduate's student-loan debt has reached at least $19,400. In
addition, figures for 2000 showed that graduates had average credit
card debt of around $2,750.
In the law study, about 68 percent of public interest employers
surveyed - government offices, legal aid organizations, public
defenders and other nonprofit groups - reported recruiting
difficulties. Most blamed the combination of low starting salaries
and high law school loans for discouraging law students from public
service jobs.
The report encourages law schools and employers to create
programs to help students who choose public service pay back loans
in their lower-paying jobs. A few schools, including Harvard, New
York and Georgetown universities, already have them.
The median starting salary last year at private law firms, was
$90,000. By contrast, public interest groups pay new graduates
about $35,000, while government pays $40,000 to $45,000.
```  
At the end of this file, the command will exit the file. This can be useful for short files like this, since it can be viewed on one page, and after viewing scrolling will exit the file making it more efficient.  
Command-Line Option:  
[https://ss64.com](https://ss64.com/bash/less.html)





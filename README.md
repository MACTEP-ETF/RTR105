# RTR105
Studiju kursa Datormācība (pamatkurss) elektroniskā klade  
# Vispārīgi
## Hardware (PC sastāvdaļas):
- CPU;  
- RAM (short);  
- ROM (long);  
- Perifērijas ierīces (pele, tastatūra, monitors utt.);
- Divi pamatelementi – "0" un "1".  

# Darba vides struktūra
1. **Hardware** – dzelzis.  
2. **OS Linux operētājsistēma** – sazinās ar dzelzi izmantojot *drivers* (iebūvētās instrukcijas).  
3. **Bash interpretators** – sazinās ar OS Linux izmantojot *Shell* valodu.  
4. **Applications** – Aplikācijas. 

# LINUX
## Termināls
### Interfeiss  
**user@epk428-2:/home$**:
- **user** – lietotāja vārds;  
- **epk428** – serveris;  
- **2** – darba stacijas numurs;  
- **/home$** – tekošais folderis.  
Ja objekta nosaukums sākas ar ".", tad objekts ir režīmā ***hidden***.

### Īsceļi (shortcuts)
**Ctrl+Alt+T** – jauna termināla loga atveršana.  
**Ctrl+Shift+T** – jauna papildloga atveršana esošajā termināla.  

## Bash interpretators
### Īsceļi (shortcuts)
**Ctrl+L** – ekrāna attīrīšana (*Clear screen*).  
**TAB 2x** – papildina kodu uzrādot iespējamos variantus.  
**TAB 1x** – papildina kodu ar vienīgo iespējamo variantu.  
### Komandas
#### Failu sistēmas navigācija
**pwd** – kur es esmu? (*Kāda ir adrese tekošam folderim*).  
**ls** – kas man ir pieejams (*Kas atrodas tekošā folderī*).  
**ls -a** – parādā arī paslēptos objektus (*hidden*).  
**ls -al** – tekošā foldera detalizēts skats. (Piem., **drwxr-xr-x**, kur "d" – direktorija; "r" – read; "w" – write; "x" – execute).  
**cd .** – norāde/solis uz vietas (*relatīvā adresācija*).  
**cd ..** – norāde/solis līmeni augstāk.  
**~$** – mājas apgabals.  
**cd /home** – pāreja uz konkrētu adresi (folderi).  

#### Apraksts par sistēmu
**whoami** – kas es esmu? (*Lietotājs*).  
**uname** – operētājsistēmas nosaukums.  
**echo $0** – noklusētā interpretatora nosaukums.  
**sh** – kompaktā interpretatora izsaukšana.  
#### Vispārīgi
**firefox** – Firefox palaišana.  
**man** – dod detalizēts apraksts par tekošu kodu (*Jāpieraksta pirms nepieciešamās komandas*).  
**history** – parāda uz ekrāna visas veiktās operācijas/komandas.  
**>** – konveijera simbols. konkrētas informācijas ierakstīšana failā (*Piem., history > File.txt*).  
**init 0** – OS Linux shutdown.  

*УНДЭРКОНСТРУКТИОН*  

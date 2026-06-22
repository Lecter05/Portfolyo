# Enes Bayram

* Statik ve Dinamik zararlı yazılım analizi, Tespit kuralı geliştirme (SIEM/SOAR), olay müdahalesi, disk ve bellek adli bilişimi.
* Aktif olarak Windows forensic lab çözümleri ve BYOVD - EDR kill senaryosu için kural geliştirme çalışmaları ile ilgileniyorum.

[LinkedIn](https://www.linkedin.com/in/enes-bayram-624bab252) • [Medium](https://medium.com/@Lecter901)

---

# Yetenekler

`Adli bilişim`: FTK ile imaj alma, KAPE ile artifact toplama, Eric Zimmerman araç setini (MFT, UsnJrnl, prefetch, Amcache, registry hive'ları) kullanarak saldırıyı Initial Access'ten C2'ye kadar timeline üzerinden yeniden kurup raporlama.

`Tespit ve otomasyon`: Splunk (SIEM), Tines & Phantom (SOAR), tespit kuralı geliştirme, Atomic Red Team ile FP tuning.

`Zararlı yazılım analizi`: REMnux, FLARE VM, statik ve dinamik analiz, x64dbg, IOC çıkarma ve rapor haline getirme.

`Ağ adli bilişimi`: Zeek (Zui), Suricata, Wireshark ile PCAP analizi.

---

# Projeler

### Gmail Phishing SOAR Playbook 

Tines'ta oluşturduğum playbook, mail header'ını parse edip gönderici IP'sini, URL'leri ve ekleri VirusTotal ile kontrol ediyor, blacklist/whitelist'e bakıyor ve zararlıysa maili otomatik çöpe taşıyor. [İncele](https://github.com/Lecter05/Gmail-Phishing-Detection-Playbook)
<img width="1225" height="938" alt="image" src="https://github.com/user-attachments/assets/ba3e16e6-30dc-4006-8775-f5e21dc2668d" /> 



### IR Bilgi Tabanı

SANS cheat sheet’lerinden yararlanarak oluşturduğum ve aktif olarak geliştirdiğim etkileşimli bilgi tabanıdır. ATT&CK adımlarına göre REGISTRY, FILE SYSTEM, EVENT LOG gibi kaynaklarda hangi bilgiler bulunabilir, Lateral Movement, Memory Forensic konularında hızlı triyaj tarifleri sağlar. [İncele](https://lecter05.github.io/IR-Referans)

[<img width="1919" height="946" alt="bilgi t" src="https://github.com/user-attachments/assets/e53ea6a8-d71f-402a-8db3-524da25f50d3" />](https://lecter05.github.io/IR-Referans)

### SIEM Tespit ve SOAR Otomatik Müdahale

Splunk'ta LSASS dump ve shadow copy delete için tespit kuralları yazıp kuralları Atomic Red Team ile tetikleyip FP tuning yaptım. Oluşan alarmı Phantom'a (SOAR) ilettim, WinRM üzerinden çalışan PowerShell betiği hedef makineyi ağdan izole eden kurgu inşa ettim.

https://github.com/user-attachments/assets/55aa8085-54d4-463a-8763-15cb151b5256

---

# Yazılarım

* CyberDefenders'ın hard seviye lablarından APT34 senaryosunda saldırı zincirini Initial access'ten exfiltration'a kadar adım adım analiz edip yazı haline getirdim. [İncele](https://medium.com/@Lecter901/cyberdefenders-recruiter-hanoi-op-lab-4cd26eed2f90)

* Bellek analizi ve CTF soru çözümlerinin yer aldığı yazı. [İncele](https://github.com/Lecter05/Security-Writeups)

# Sertifikalar
* Malware Analysis Skill Path [LetsDefend](https://app.letsdefend.io/certificate/show/7c794b15-c487-4c89-af70-7015a57e0755) 
* Incident Responder Learning Path [LetsDefend](https://app.letsdefend.io/certificate/show/dc28e845-b82d-4495-a79d-79ac286ce7db) 
* SOC Analyst Learning Path [LetsDefend](https://app.letsdefend.io/certificate/show/a3b8def7-0b0c-40c1-8ddd-cd9fe7ab140a) 
* Windows ve Linux Olay Müdahale [Siber Kulüpler Birliği](https://siberkulupler.com/cert/SKB-2025-PCZZS) 







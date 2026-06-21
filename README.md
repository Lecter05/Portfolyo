# Çalışma alanlarım

Tespit kuralı geliştirme (SIEM/SOAR), olay müdahalesi, disk ve bellek adli bilişimi, statik ve dinamik zararlı yazılım analizi.

Aktif olarak Windows forensic lab çözümleri ve BYOVD - EDR kill senaryosu için kural geliştirme çalışmaları ile ilgileniyorum.

[LinkedIn](https://www.linkedin.com/in/enes-bayram-624bab252) • [Medium](https://medium.com/@Lecter901)

---

# Yetenekler

`Adli bilişim`: FTK ile imaj alma, KAPE ile artifact toplama, Eric Zimmerman araç setini (MFT, UsnJrnl, prefetch, Amcache, registry hive'ları) kullanarak saldırıyı Initial Access'ten C2'ye kadar timeline üzerinden yeniden kurup raporlama.

`Tespit ve otomasyon`: Splunk (SIEM), Tines & Phantom (SOAR), tespit kuralı geliştirme, Atomic Red Team ile FP tuning.

`Zararlı yazılım analizi`: REMnux, FLARE VM, statik ve dinamik analiz, x64dbg, IOC çıkarma ve rapor haline getirme.

`Ağ adli bilişimi`: Zeek (Zui), Suricata, Wireshark ile PCAP analizi.

---

# Projeler

### Gmail Phishing Playbook

Tines'ta oluşturduğum playbook, mail header'ını parse edip gönderici IP'sini, URL'leri ve ekleri VirusTotal ile kontrol ediyor, blacklist/whitelist'e bakıyor ve zararlıysa maili otomatik çöpe taşıyor.

Video ve PDF'i incelemek için [Github](https://github.com/Lecter05/Gmail-Phishing-Detection-Playbook)

### IR Bilgi Tabanı

SANS cheat sheet’lerinden yararlanarak oluşturduğum ve aktif olarak geliştirdiğim etkileşimli bilgi tabanıdır. ATT&CK adımlarına göre REGISTRY, FILE SYSTEM, EVENT LOG gibi kaynaklarda hangi bilgiler bulunabilir, Lateral Movement, Memory Forensic konularında hızlı triyaj tarifleri sağlar.

[Canlı site](https://lecter05.github.io/IR-Referans)

<img width="1919" height="946" alt="bilgi t" src="https://github.com/user-attachments/assets/e53ea6a8-d71f-402a-8db3-524da25f50d3" />

### SIEM Tespit Geliştirme ve SOAR ile Otomatik Müdahale

Splunk'ta LSASS dump ve shadow copy delete için tespit kuralları yazıp kuralları Atomic Red Team ile tetikleyip FP tuning yaptım. Oluşan alarmı Phantom'a (SOAR) ilettim, WinRM üzerinden çalışan PowerShell betiği hedef makineyi ağdan izole eden kurgu inşa ettim.

---

# Yazılarım

* CyberDefenders'ın hard seviye lablarından APT34 senaryosunda saldırı zincirini Initial access'ten exfiltration'a kadar adım adım analiz edip yazı haline getirdim. [Yazı linki](https://medium.com/@Lecter901/cyberdefenders-recruiter-hanoi-op-lab-4cd26eed2f90)

* Bellek analizi ve CTF soru çözümlerinin yer aldığı yazı. [Yazı linki](https://github.com/Lecter05/Security-Writeups)

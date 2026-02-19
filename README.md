# 🚩 HTB-Pwned

Hack The Box platformasındakı maşınların həlləri, qeydlərim və istifadə etdiyim exploit kodlarının toplandığı repodur.

## 📁 Reponun Strukturuna Baxış

Hər bir maşın üçün ayrıca qovluq yaradılıb və içərisində aşağıdakılar mövcuddur:
* **Nmap:** Skan nəticələri.
* **Exploits:** İstifadə olunan scriptlər.
* **Notes.md:** Maşının həll yolu (write-up).

---

## 🛠️ İstifadə Olunan Alətlər

Maşınların həlli zamanı əsasən bu alətlərdən istifadə edirəm:

| Alət | Məqsəd |
| :--- | :--- |
| **Nmap** | Port skan və servis analizi |
| **Burp Suite** | Web trafik analizi |
| **Gobuster / Feroxbuster** | Directory brute-force |
| **Metasploit** | Exploit idarəetməsi |
| **Netcat** | Reverse shell bağlantıları |

---

## 🚀 Başlamaq Üçün

Bu reponu öz lokal maşınınıza klonlamaq üçün:

```bash
git clone git@github.com:vitasec/HTB-Pwned.git
cd HTB-Pwned

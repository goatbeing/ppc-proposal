# Description of Updated CSV File

The current CSV database used for the **Prepunk Club** on vision contains many entries with missing names, though their hashes are available on Vision's collections github. This was previously intentional: a script from Vision.io was run manually to populate the names and assign them to their correct category. This approach was exclusive to the Prepunk Club and was not used for sub-categories of it like 1k, 10k, Spanish, or Digits.

However, it has been several years since then, and database is pretty much outdated with the script not running consistently, and as a result, newly registered names have not been properly updated in the database. Upon further investigation, additional discrepancies were discovered—such as missing hashes, incorrect names, and outdated information—particularly in the Vision database located at:  
`Zimtente/ens-collections/blob/main/collections/pre-punk-club.csv`

It's important to note that running the script won't be sufficient as the database itself has many critical inaccuracies.

## Summary
- The Vision database is outdated and it's causing inconsistency between names across Prepunk categories.
- It includes incorrect names that are not part of the Prepunk Club.
- A total of **1,328** names/hashes are missing.
- Prepunk (YES/NO) Filters not functioning right on Vision due to this.

## About the Updated CSV Files
- The attached CSV files contain a complete list of **79,720 hashes** with only **591 missing names** in order of `finalizedAuction` event date for Prepunk Club names. These files include:
  - Hashes for entries with missing names.
  - Proper formatting for compatibility with Vision.io (`name,tokenid` format in CSV).
  - Subcategory files are also included (1k, 10k).
  

> **Note:** Row 16, with a hash value of `0`, is a well-known anomaly caused by the smart contract back in 2017. It is included here for the sake of data accuracy, but it cannot be owned or registered and may be excluded if desired.

> **Note:** Thousands of entries in the new database were bruteforced to find matching name for hashes and their label name is not yet known to the ENS registry. This may pose a incompatibility with how Visin.io works.

---

# Description of Categories

### Prepunk 1k  
The first 1,000 ENS names ever registered during the initial auction, predating CryptoPunks from 9 May 2017 to 23 June 2017.

### Prepunk 10k  
The first 10,000 ENS names ever registered during the initial auction, predating CryptoPunks from 9 May 2017 to 23 June 2017.

### Prepunk  
Collection of the first ENS names ever registered during the initial auction, predating CryptoPunks from 9 May 2017 to 23 June 2017.

### Digits  
Collection of Digits-Only ENS names ever registered during the initial auction, predating CryptoPunks from 9 May 2017 to 23 June 2017.

### Spanish  
Collection of Spanish ENS names ever registered during the initial auction, predating CryptoPunks from 9 May 2017 to 23 June 2017.

> **Note:** We aim to detach the "Club" suffix from Prepunk names. Prepunk is an actual, on-chain provable trait that was first defined by Makoto, an ENS developer. Using the "Club" suffix is misleading, not genuine, and we believe "Club" should refer to the community surrounding these historical assets—not the names or categories themselves. Prepunk Club will eventually become a place to learn about the history of Prepunk names.


---

# Links

**Website:**  
[https://prepunk.club/](https://prepunk.club/)

**Verify tool:**  
[https://verify.prepunk.club/](https://verify.prepunk.club/)

**Database:**  
[https://verify.prepunk.club/list](https://verify.prepunk.club/list)

**Docs:**  
[https://docs.prepunk.club/](https://docs.prepunk.club/)

**Discord:**  
[https://discord.com/invite/XSudfGtVCx](https://discord.com/invite/XSudfGtVCx)

**X/Twitter:**  
[https://x.com/prepunkofficial](https://x.com/prepunkofficial)

**Email:**  
team@prepunk.club

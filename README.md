

# **Blind-Signature-Based E-Voting Platform on Ethereum**  

## **Overview**  
This project is a proof-of-concept implementation of a **blind-signature-based e-voting system** on Ethereum, designed to ensure **secret ballots** while maintaining **gas efficiency**. Unlike traditional blockchain-based voting protocols, which either lack ballot secrecy or become impractical due to high transaction costs, this implementation offers a balanced solution by leveraging **blind signatures** to anonymize votes while keeping gas costs constant.  

## **Motivation**  
Existing blockchain-based voting solutions have significant limitations:  
- **Public visibility of votes**: Many Ethereum-based voting mechanisms do not provide secret ballots, exposing voters' choices to the public.  
- **High gas costs**: Advanced cryptographic voting protocols, such as the **Open Vote Network (OVN)**, suffer from inefficiency, as gas costs increase with the number of participants, making large-scale elections impractical.  

To overcome these challenges, **I** developed an e-voting protocol that ensures **voter privacy** while keeping the transaction cost per vote constant at approximately **200k gas** (unoptimized).  

## **Key Features**  
✔ **Blind-Signature-Based Voting** – Voter choices remain private, ensuring secret ballots.  
✔ **Gas-Efficient Design** – Unlike traditional protocols, our system maintains a constant gas cost per vote.  
✔ **Decentralized & Secure** – Built on Ethereum, ensuring transparency and immutability.  
✔ **Open-Source & Extensible** – A proof-of-concept designed for experimentation and further research.  

## **Limitations & Considerations**  
⚠ **Proof of Concept** – The system may contain critical bugs and should not be used for mission-critical elections.  
⚠ **Coercion Vulnerability** – Like other blockchain-based voting schemes, this system is **not coercion-resistant**. Voters can prove their vote to attackers in exchange for rewards.  

## **Use Cases**  
🔹 **University or Club Elections** – Small-scale, non-critical voting scenarios.  
🔹 **Community Governance** – DAO-based decision-making with privacy guarantees.  
🔹 **Experimental Research** – A foundation for improving blockchain-based voting protocols.  

This project highlights the potential of **privacy-preserving, decentralized voting** on Ethereum and opens avenues for further improvements in blockchain-based governance systems.  



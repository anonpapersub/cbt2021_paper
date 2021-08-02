# Augmenting MetaMask to support TLS-endorsed Smart Contracts
> CBT 2021
>
> 5<sup>th</sup> International Workshop on Cryptocurrencies and Blockchain Technology

blinded, blinded and blinded

University, City, State, Country

{mailaddresses}@university.edu

## Abstract

> Users in blockchain systems are exposed to address replacement attacks due to the weak binding between websites and smart contracts, as they have no way to verify the authenticity of obtained addresses. Prior research introduced TLS-endorsed Smart Contracts (TeSC) that equip Smart Contracts with authentication information, proving the relation to the domain name of the respective website. For an efficient and user-friendly approach, this technology needs to be integrated with wallets. Based on the analysis of browser warnings regarding TLS-certificates, we augment MetaMask with the ability to detect TeSC and warn users if attack scenarios are detected. To evaluate our work, we conduct a study with 40 participants to show the effectiveness of TeSC to prevent address-replacement attacks and ensure the safe interaction of users and addresses. 

## Note to reviewers
If you are interested in reading the paper that we build upon, you can find a [blinded version here](paper/paper_blinded.pdf). Nonetheless, the background chapter should provide sufficient information to review paper without reading this additional paper. 


## Presentation & Slides
TBD

## Paper
TBD

## Analysis

### Browser URL Bars
All browsers choose different approaches to highlight sub-parts of the URL in the address bar and have slightly different approaches for indicating a security downgrade.

[Browser URL bars](/img/Brow_PosAddressbar.png)
[Browser URL bars downgrade](/img/Brow_DownGradeIndication.png)

### Conceptual Models for error pages

#### Firefox
[Overridable Error](/img/Brow_ConceptualModelFFOverridable.pdf)
[Critical Error](/img/Brow_ConceptualModelFFCriticalError.pdf)


#### Chrome/Edge  
[Error Page Chrome and Edge](/img/Brow_PosAddressbar.png)

### Downgrade Algorithm
[Downgrade Algorithm for TeSC](/img/DownGrade_Algorithm.png)

## Design

### Conceptual Models for TeSC error pages
[Conceptual Models for TeSC error pages](/img/TeSCErrorConceptualModel.png)

### Verification Flow
[Flow diagram of the TeSC verification algorithm](/img/TeSCErrorConceptualModel.png)

## Evaluation

[Introduction to Blockchain and MetaMask](/pdf/helptext.pdf)


### Contract Addresses

| Contract Name       | Address                                    |
|---------------------|--------------------------------------------|
| TeSCRegistry        | 0x0678D9838740c79170139e6d48b86b71460795c2 |
| GreatCoin Contract  | 0x919d5FD953e9F268985e792aD9E43F99AbB979dd |
| Bad Contract        | 0x1566E143b59ba6590d52D6fB3bf2fc4f6e7d5ebF |
| Participant Account | 0x5C553867B3B01D4F2e68B0070c1E84e1e12E4A0C |

### E-Mails from Alice

[First email](/pdf/Experiment_Text.pdf)
[Second email](/pdf/Experiment_Text2.pdf)
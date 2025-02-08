# 🃏 The Ultimatum Game – Code Review Edition  

## 📜 Game Rules  
1. **Proposer:** You receive **$100** (hypothetically). You must decide how much to offer your partner.  
2. **Responder:** Your partner will review your offer and either:  
   - **Accept**: Both of you receive the proposed amounts.  
   - **Reject**: Neither of you gets anything.  
3. **Decision Format:** The offer will be submitted as a pull request, and the response will be given as a comment on that PR.  

---

## 🚀 How to Play in GitHub  

### 🔹 Step 1: Fork & Clone the Repo  
- Each pair forks this repository and clones it locally.  

### 🔹 Step 2: Proposer Submits Offer  
- The proposer creates a new text file named **`yourname.txt`** (e.g., `alice.txt`).  
- Inside the file, they write:  

  ```txt
  I offer $X to my partner.
  ```
- They commit and push their file, then open a pull request.

### 🔹 Step 3: Responder Reviews the Offer
- The responder visits the PR and leaves a comment:
- Accept: “I accept this offer.”
- Reject: “I reject this offer.”
- If rejected, both get $0 (but more experience!).
### 🔹 Step 4: Proposer Merges or Closes the PR
- If accepted, the proposer merges the PR.
- If rejected, the proposer closes the PR without merging.

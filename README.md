# 🃏 The Ultimatum Game – Code Review Edition  

## 📜 Game Rules  
1. **Proposer:** You receive **10 pts** in OOSE (hypothetically). You must decide how much to offer your partner.  
2. **Responder:** Your partner will review your offer and either:  
   - **Accept**: Both of you receive the proposed amounts.  
   - **Reject**: Neither of you gets anything.  
3. **Decision Format:** The offer will be submitted as a pull request, and the response will be given as a comment on that PR.  

---

## 🚀 How to Play in GitHub  

### 🔹 Step 1: Proposer Submits Offer  
- The proposer creates a new text file named **`yourname.txt`** (e.g., `alice.txt`).  
- Inside the file, write:  

  ```txt
  I offer $X to my partner.
  ```
- Commit and push your file, then open a pull request.

### 🔹 Step 2: Responder Reviews the Offer
- The responder visits the PR and leaves a comment:
   - Accept: “I accept this offer.”
   - Reject: “I reject this offer.”
- If accepted, the responder merges the PR.
- If rejected, the responder closes the PR without merging.

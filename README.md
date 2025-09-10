# Document Signing Application - Take Home Assessment

## 🎯 Overview

Welcome to the Novoflow founding engineer take-home assessment. Build a minimal document signing application that demonstrates your ability to create a polished, functional product quickly.

**Time Expectation:** 2-4 hours  
**AI Tools:** You're encouraged to use Cursor, Claude, or any AI coding assistants  
**Focus:** We care mostly about your design decisions, code quality, and user experience.

---

## 📋 Linear Ticket: CORE-001

### Build Document Signing MVP

**Priority:** P0 - Critical  
**Type:** Feature  
**Estimate:** 3 points  

### The Challenge

Create a document signing application where users can:
1. Upload a PDF document
2. Place signature fields on it
3. Sign the document
4. Download the signed version

### Core Requirements (Must Have)

#### 📄 Document Upload & Display
- [ ] Upload a PDF file (or accept a URL to a PDF)
- [ ] Display the PDF in the browser
- [ ] Store the document (can be in-memory/localStorage for simplicity)

#### ✍️ Signature Placement & Signing
- [ ] Click on the PDF to add signature fields
- [ ] Allow users to type or draw their signature
- [ ] Apply signature to the document
- [ ] Generate a signed version (can be visual overlay)

#### 💾 Save & Export
- [ ] Save the signed document state
- [ ] Export/download the signed document (PDF or image)

### Nice to Have (If Time Permits)
- Multiple pages support
- Multiple signature fields
- Drag to reposition signature fields
- Date/time stamps
- Simple authentication (can be mock)
- Email the signed document (can be simulated)

### Technical Guidelines

#### What We're Looking For:
- **Clean, intuitive UI** - Should feel professional
- **Smooth user experience** - Minimal clicks to complete signing
- **Smart technical choices** - Use libraries that make sense
- **Code organization** - Show you can structure a codebase
- **Error handling** - What happens when things go wrong?

#### Suggested Tech Stack:
- Next.js (already set up)
- Any PDF library (react-pdf, pdf.js, etc.)
- Any signature library (signature_pad, react-signature-canvas, etc.)
- Tailwind CSS (already included)
- Any state management you prefer

### What's Not Required
- Authentication or user accounts
- Multiple users/signers
- Email workflows
- Database storage
- Mobile optimization
- Production-level security

### Deliverables

1. **Working Application**
   ```bash
   npm install
   npm run dev
   # Opens at http://localhost:3000
   ```

2. **Brief Write-up** (Update this README)
   - How to run the application
   - Key technical decisions and trade-offs
   - What you would improve with more time

---

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Open http://localhost:3000
```

## 📚 Helpful Libraries

Consider these options (not required):

**PDF Handling:**
- `react-pdf` - Display PDFs
- `pdf-lib` - Modify PDFs
- `pdfjs-dist` - Mozilla's PDF.js

**Signatures:**
- `react-signature-canvas` - Draw signatures
- `signature_pad` - Smooth drawing

**UI:**
- `shadcn/ui` - Pre-built components
- `radix-ui` - Headless components

## 📝 Submission Instructions

**IMPORTANT: Do NOT fork this repository** 

To maintain confidentiality of your solution:

1. Clone and create a **PRIVATE** repository in your own GitHub account
2. Build your solution
3. Update this README with your notes
4. Add `@zesquirrelnator` as a collaborator when ready to submit
5. Send the private repo link to georges@novoflow.io

---

**Questions?** Make reasonable assumptions and document them.

Contact: georges@novoflow.io
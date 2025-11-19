# The Coffee License: Arguments Against Validity and Enforceability

*A critical legal analysis of why The Coffee License fails as an open source license and faces significant enforceability challenges*

---

## Executive Summary

While The Coffee License represents a creative attempt to address the economic challenges facing independent developers, it fails to qualify as a valid open source license under established definitions and faces substantial legal barriers to enforcement. This document outlines the key arguments against its validity and enforceability.

---

## Part I: Not a Valid Open Source License

### 1. Fails the Open Source Definition (OSD)

The Open Source Initiative (OSI) maintains the authoritative definition of "open source." The Coffee License violates multiple OSD criteria:

#### Criterion 5: No Discrimination Against Persons or Groups
> "The license must not discriminate against any person or group of persons."

The Coffee License explicitly discriminates against entities based on their financial status. Organizations with net worth above $500M are treated differently from those below—a clear violation of this principle.

#### Criterion 6: No Discrimination Against Fields of Endeavor
> "The license must not restrict anyone from making use of the program in a specific field of endeavor."

By requiring commercial entities above a certain size to pay fees, the license effectively restricts large-scale commercial use unless payment is made, creating a barrier to certain fields of endeavor.

#### Criterion 10: License Must Be Technology-Neutral
While not directly violated, the license's dependence on determining "net worth, market cap, or enterprise value" creates technological and practical barriers to compliance that undermine neutral application.

### 2. Not Recognized by Any Major License Organization

- **Not OSI-approved**: Cannot be marketed as "Open Source" under OSI guidelines
- **Not FSF-approved**: Does not appear on the Free Software Foundation's license list
- **Not SPDX-listed**: Lacks a standard identifier in the Software Package Data Exchange
- **Not Fedora/Debian compliant**: Would not pass distribution guidelines

### 3. Violates Free Software Foundation's Four Freedoms

The FSF defines free software through four essential freedoms:

- **Freedom 0**: Run the program as you wish, for any purpose
- **Freedom 1**: Study and modify the source code
- **Freedom 2**: Redistribute copies
- **Freedom 3**: Distribute modified versions

The Coffee License conditions these freedoms on financial status, meaning large entities do NOT have these freedoms until they pay—a fundamental violation.

### 4. Incompatible with Existing Open Source Ecosystem

- Cannot be combined with GPL, Apache, or MIT code in many scenarios
- Creates license compatibility nightmares for downstream projects
- Organizations cannot safely include this software in larger projects

---

## Part II: Enforceability Challenges

### 1. Definitional Ambiguity

The license uses terms without precise definitions:

#### "Net Worth"
- Different accounting standards (GAAP, IFRS) calculate this differently
- Does this include subsidiaries? Parent companies? Joint ventures?
- What about nonprofit organizations with large endowments?
- How is debt factored in?

#### "Market Cap"
- Only applies to publicly traded companies
- Fluctuates daily—what date determines compliance?
- Many large private companies have no market cap

#### "Enterprise Value"
- Complex calculation involving debt, cash, and market cap
- Varies by valuation methodology
- Private companies require expensive appraisals

### 2. Measurement and Verification Problems

**Who determines net worth?**
- The licensee? (conflict of interest)
- The licensor? (lacks access to financial data)
- Independent auditor? (expense and logistics)

**When is it measured?**
- At time of download?
- At time of deployment?
- Annually? Quarterly?
- What if company crosses threshold mid-project?

**Practical impossibility:**
- Many organizations genuinely don't know their net worth
- Private companies have no obligation to disclose
- International organizations face currency conversion issues

### 3. Contract Formation Issues

#### Lack of Mutual Assent
For a contract to be enforceable, both parties must agree to the same terms. How does the licensor know if a mega-corp entity has used the software? There's no click-through, no signature, no manifest acceptance.

#### Consideration Problems
Traditional contract law requires consideration from both parties. The free tier provides software for nothing in return—arguably a gift, not a contract.

#### Statute of Frauds
Some jurisdictions require certain contracts to be in writing and signed. A license file in a repository may not satisfy these requirements for commercial licensing agreements.

### 4. Jurisdictional Nightmares

#### Which Law Applies?
- Developer's jurisdiction?
- Company's jurisdiction?
- Where the software runs?
- Where the end users are?

#### International Enforcement
- No international treaty covers open source license enforcement
- Net worth thresholds in USD discriminate against non-US entities
- Exchange rate fluctuations create compliance uncertainty

#### Choice of Forum
The license specifies no venue for disputes, meaning:
- Developer may need to sue in corporate defendant's jurisdiction
- Cost of international litigation exceeds any potential recovery
- $50 fee makes litigation economically irrational

### 5. Remedies and Damages

#### What are the actual damages?
- License fee is only $50
- No statutory damages provision
- Actual damages are nearly impossible to prove
- Attorney fees likely exceed any recovery by 100x

#### Injunctive Relief
- Courts rarely grant injunctions for freely available software
- Open source nature undermines irreparable harm arguments
- Balance of hardships favors large company

#### Specific Performance
- Requiring payment of $50 through litigation is absurd
- Courts have discretion to deny specific performance
- Practical futility doctrine may apply

### 6. Compliance Impossibility for Complex Organizations

#### Conglomerate Problem
- Is Disney's net worth relevant to ESPN's software use?
- What about wholly-owned subsidiaries?
- Joint ventures with mixed ownership?
- Franchise systems?

#### Government and Quasi-Governmental Entities
- What is the "net worth" of a government agency?
- State-owned enterprises?
- Sovereign wealth funds?

#### Restructuring Events
- Mergers and acquisitions mid-license
- Bankruptcy proceedings
- Spin-offs and divestitures

---

## Part III: Practical Unworkability

### 1. No Enforcement Mechanism

The license provides no way to:
- Discover violations
- Audit compliance
- Track software distribution
- Identify corporate users

Without telemetry or registration, enforcement is theoretical only.

### 2. Chilling Effect on Adoption

- Corporate legal departments will reject this license
- Risk-averse companies will choose MIT/Apache alternatives
- The uncertainty reduces adoption, defeating the license's purpose

### 3. Gaming and Evasion

Bad actors can easily circumvent:
- Use shell companies or subsidiaries under threshold
- Claim net worth is below threshold without verification
- Incorporate in jurisdictions with favorable accounting
- Use contractors or vendors as intermediaries

### 4. No Cure Period

The license has no provision for:
- Good faith errors in calculation
- Opportunity to cure non-compliance
- Grace period after crossing threshold

This all-or-nothing approach is unusual in commercial licensing.

---

## Part IV: Precedent and Industry Practice

### 1. Failed Similar Experiments

- **Commons Clause**: Widely criticized, limited adoption
- **Server Side Public License (SSPL)**: Rejected by OSI
- **Elastic License**: Not considered open source
- **Business Source License**: Explicitly not open source

### 2. Successful Dual Licensing Works Differently

Projects like Qt and MySQL succeed because they:
- Offer GPL (true open source) as free option
- Commercial license removes copyleft restrictions
- Clear value proposition for commercial license
- Professional enforcement infrastructure

The Coffee License offers no differentiated value for the commercial license—just the same MIT-style terms.

---

## Conclusion

The Coffee License, despite its well-intentioned goals, fails to meet established criteria for open source licensing and faces insurmountable enforceability challenges. Its definitional ambiguities, measurement impossibilities, jurisdictional complexities, and practical enforcement barriers render it more of a philosophical statement than a legally operative document.

Developers seeking to monetize their work while maintaining open source principles should consider:
- True dual licensing (GPL + commercial)
- Open core models
- Support/service-based monetization
- Sponsorship platforms (GitHub Sponsors, Open Collective)

The Coffee License represents creative thinking about open source economics but is neither a valid open source license nor a reliably enforceable legal instrument.

---

*Disclaimer: This document presents arguments for analytical purposes and does not constitute legal advice. Consult qualified legal counsel for specific situations.*

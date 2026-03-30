# Cybercrime Case Study: UPI Payment Fraud

## Crime Type
UPI (Unified Payments Interface) Fraud / Online Payment Fraud

## Case Study: The "Electricity Bill" Scam

### Scenario Overview
Last month, Rohan, a 2nd-year engineering student in Bangalore, received a WhatsApp message stating that his electricity bill was overdue and his power would be cut off within 2 hours unless he paid immediately. The message contained a link to "paytm-electricity-bill.in" (a fake domain designed to look like Paytm).

### Step-by-Step Attack Process

1. **Initial Contact:** Rohan received an urgent message creating panic about power disconnection during his exam week.

2. **Fake Urgency:** The message stated "Action required within 2 hours" pushing him to act fast without thinking.

3. **Malicious Link:** He clicked the link which opened a page identical to Paytm's payment interface, complete with logos and formatting.

4. **Data Harvesting:** The fake site asked for his UPI ID and then redirected to a page mimicking the UPI app interface asking for his UPI PIN.

5. **Unauthorized Transaction:** The moment he entered the PIN, ₹15,000 was deducted from his account in three quick transactions of ₹5,000 each.

6. **Disappearance:** The website went offline within hours, and the WhatsApp number became unreachable.

### Target Profile
- College students who are relatively new to handling their own bill payments
- People living away from home for the first time in hostels/PGs
- Individuals who panic easily when faced with service disconnection threats
- Users who trust familiar brand names (Paytm, Google Pay) without checking URLs

### Consequences
- **Financial:** Immediate loss of ₹15,000—significant amount for a student
- **Emotional:** Stress and anxiety affecting exam preparation
- **Privacy:** Compromised UPI ID potentially leading to further phishing attempts
- **Time:** Multiple bank visits and cyber crime reporting procedures
- **Educational:** Had to borrow money from friends to manage monthly expenses

### Source Reference
*Based on common patterns reported on cybercrime.gov.in and consumer forums. This represents a realistic composite of actual incidents reported in Indian colleges during 2024-2025.*

## Analysis
This scam works because it exploits two things: fear of immediate consequences (no electricity) and trust in familiar interfaces. Students are targeted because they're often managing bills independently for the first time and may not verify URLs carefully. The fake website looked exactly like the real payment app, making visual detection difficult. The urgency ("2 hours") prevents victims from verifying with roommates or family.
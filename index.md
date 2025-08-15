# Property Listing

## 🏠 Property Overview

<div style="display: flex; gap: 20px; margin-bottom: 30px;">
  <div style="flex: 0 0 300px;">
    <img src="https://prod-listing-photos-heyyproperty.s3.us-east-1.amazonaws.com/listings/1ad75a15-2691-455c-a7dd-6e35d5e70a21/IMG_4708.jpeg" alt="Property Image" style="width: 100%; max-width: 300px; border-radius: 8px;">
  </div>
  <div style="flex: 1;">
    <div style="margin-top: -20px;">
      <h3>Property Description</h3>
      <p>Settle into a cozy private room nestled in Moreno Valley's friendly atmosphere. This community has a blend of accessibility and comfort, perfect for busy lifestyles and peaceful unwind time. Whether you're studying, working from home, or seeking a quiet space, this property has a welcoming vibe that feels like home.</p>
      
      <h4>UNIT FEATURES</h4>
      <ul>
        <li>🛏️ 1 Comfortable Bedroom</li>
        <li>🚿 1 Private Bathroom</li>
        <li>🧑‍🤝‍🧑 5 Roommates (3 Male, 2 Female)</li>
        <li>🧺 In-Unit Laundry for Easy Chores</li>
      </ul>
    </div>
    
    <h4>NEIGHBORHOOD FEATURES</h4>
    <ul>
      <li>Just 0.3 mi to Dutch Bros Coffee for your daily caffeine fix</li>
      <li>Relax at Towngate Memorial Park, only 0.9 mi away</li>
      <li>Quick trips to local shops like The Home Depot (0.5 mi) for essentials</li>
      <li>Easy access to Moreno Valley Mall (0.9 mi) for shopping and dining</li>
    </ul>
    
    <h4>Other Details</h4>
    <ul>
      <li>Available starting August 6, 2025</li>
      <li>No pets allowed</li>
      <li>Fixed lease available, month-to-month and subleasing are not permitted</li>
    </ul>
  </div>
</div>

## 📋 Property Details

<div style="text-align: center; margin-bottom: 30px;">
  <h3>Listing Description</h3>
  
  <div style="display: flex; justify-content: space-between; gap: 40px; text-align: left;">
    <div style="flex: 1;">
      <ul style="list-style: none; padding: 0;">
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Property Type:</span>
          <span style="margin-left: 10px; color: #666;">house</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Rental Type:</span>
          <span style="margin-left: 10px; color: #666;">private_room</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Bedrooms:</span>
          <span style="margin-left: 10px; color: #666;">1</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Bathrooms:</span>
          <span style="margin-left: 10px; color: #666;">1</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Laundry Type:</span>
          <span style="margin-left: 10px; color: #666;">in_unit</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Private Bathroom:</span>
          <span style="margin-left: 10px; color: #666;">Yes</span>
        </li>
      </ul>
    </div>
    
    <div style="flex: 1;">
      <ul style="list-style: none; padding: 0;">
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Rent:</span>
          <span style="margin-left: 10px; color: #666;">$1000</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Minimum Monthly Income:</span> <span id="minimum_monthly_income" style="margin-left: 10px; color: #666;">$1000</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Lease Type:</span>
          <span style="margin-left: 10px; color: #666;">fixed_term_lease</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Available:</span>
          <span style="margin-left: 10px; color: #666;">8/5/2025</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Male Roommates:</span>
          <span style="margin-left: 10px; color: #666;">2</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Female Roommates:</span>
          <span style="margin-left: 10px; color: #666;">3</span>
        </li>
        <li style="margin-bottom: 15px;">
          <span style="font-weight: bold; color: #333;">Pets Allowed:</span>
          <span style="margin-left: 10px; color: #666;">No</span>
        </li>
      </ul>
    </div>
  </div>
</div>


## 📝 Renter Intake

### Pets

1. **Do you have any pets?**
   - id: `has_pets`
   - type: single-choice
   - required: true
   - options: ["Yes", "No"]
   - If "Yes":
     - 1.1 **How many dogs do you have?**
       - id: `num_dogs`
       - type: single-choice
       - required: true
       - options: ["0", "1", "2", "3+"]
     - 1.2 **What dog breed(s) do you have?**
       - id: `dog_breeds`
       - type: text
       - required: false
     - 1.3 **How many cats do you have?**
       - id: `num_cats`
       - type: single-choice
       - required: true
       - options: ["0", "1", "2", "3+"]

### Rental History

2. **Is this your first time renting?**
   - id: `new_renter`
   - type: single-choice
   - required: true
   - options: ["Yes", "No"]
   - If "No":
     - 2.1 **Have you rented any place for a year or longer?**
       - id: `has_year_long_rental`
       - type: single-choice
       - required: true
       - options: ["Yes", "No"]

3. **What is your current living situation?**
   - id: `current_living_situation`
   - type: single-choice
   - required: true
   - options: ["Homeowner / Renting", "Staying with family or friends", "School/university housing", "Short-term housing (e.g., Airbnb, hotel)", "Transitional housing/shelter", "Other"]
   - If "Other":
     - 3.1 **Please explain your living situation?**
       - id: `living_situation_explained`
       - type: text
       - required: true

### Work or Study

4. **Are you a student?**
   - id: `student`
   - type: single-choice
   - required: true
   - options: ["Yes", "No"]
   - If "Yes":
     - 4.1 **Are you an undergraduate?**
       - id: `undergraduate`
       - type: single-choice
       - required: true
       - options: ["Yes", "No"]

5. **Are you currently employed?**
   - id: `currently_employed`
   - type: single-choice
   - required: true
   - options: ["Yes", "No"]
   - If "No":
     - 5.1 **How would you pay for rent?**
       - id: `rent_payment_without_job`
       - type: single-choice
       - required: true
       - options: ["Grants or Loans", "Cosigner(s)", "Combo of Grants Loans, Cosigners", "Something else"]
       - If "Something else":
         - 5.1.1 **Please explain how you would pay rent?**
           - id: `explain_rent_payment`
           - type: text
           - required: true
   - If "Yes":
     - 5.2 **Is your income verifiable by paystubs, bank statements, etc?**
       - id: `income_verifiable`
       - type: single-choice
       - required: true
       - options: ["Yes", "No"]
       - If "No":
         - Sorry, we cannot proceed (disqualified)
     - 5.3 **Do you make at least $`minimum_monthly_income` a month?**
       - id: `makes_enough_income`
       - type: single-choice
       - required: true
       - options: ["Yes", "No"]
     - 5.4 **Have you been at your current job for at least one year?**
       - id: `has_current_job_for_year`
       - type: single-choice
       - required: true
       - options: ["Yes", "No"]
       - If "No":
         - 5.4.1 **In the last 3 years, have you worked at any job for at least one year?**
           - id: `employment_history_last_3_years`
           - type: single-choice
           - required: true
           - options: ["Yes", "No"]
           - If "No":
             - Sorry, we cannot proceed (disqualified)

### Screening Consent

6. **Are you willing to undergo a credit & background check?**
   - id: `will_do_background_and_credit_check`
   - type: single-choice
   - required: true
   - options: ["Yes", "No"]
   - If "No":
     - Sorry, we cannot proceed (disqualified)

### Basic Info

7. **What is your name?**
   - id: `name`
   - type: text
   - required: true

8. **What move in date you seeking?**
   - id: `move_in_date_requested`
   - type: text
   - required: true

9. **What is your email?**
   - id: `email`
   - type: text
   - required: true
   - validation: must match `/^[^\s@]+@[^\s@]+\.[^\s@]+$/`

10. **What is your phone number?**
    - id: `phone_number`
    - type: text
    - required: true
    - validation: US 10-digit after stripping non-digits (`/^\d{10}$/` on phone.replace(/\D/g, ""))

11. **Why are you moving?**
    - id: `moving_reason`
    - type: text
    - required: true

### Tour Preference

12. **How would you like to take the tour?**
    - id: `tour_preference`
    - type: single-choice
    - required: true
    - options: ["In person", "Virtual"]


## 🚀 Schedule Tour
### Here is the link to the scheduling
<div style="text-align: center; margin-bottom: 30px;">
  <a href="https://app.heyyproperty.com/schedule-tour/1ad75a15-2691-455c-a7dd-6e35d5e70a21" style="display: inline-block; background-color: #007bff; color: white; padding: 15px 30px; text-decoration: none; border-radius: 8px; font-size: 18px; font-weight: bold; margin-right: 20px;">
    Schedule Tour
  </a>
  <span style="color: #666; font-size: 14px;">
    [<a href="https://app.heyyproperty.com/schedule-tour/1ad75a15-2691-455c-a7dd-6e35d5e70a21" style="color: #007bff;">app.heyyproperty.com/schedule-tour/1ad75a15-2691-455c-a7dd-6e35d5e70a21</a>]
  </span>
</div>

---

### 🗒️ Instructions for AI Intake

- Ask each question above, one at a time, in order, the questions are the texts.
- Save each answer using the associated `id` as the key in a JSON object.
- For conditional questions, only include the key if the question was actually asked and answered.
- At the end, return a single JSON object with all collected answers. Omit any keys for questions that were skipped due to branching/conditionals or left unanswered.

#### Example Output

```json
{
  "has_pets": "Yes",
  "num_dogs": "1",
  "dog_breeds": "Labrador",
  "num_cats": "0",
  "new_renter": "No",
  "has_year_long_rental": "Yes",
  "current_living_situation": "Homeowner / Renting",
  "student": "No",
  "currently_employed": "Yes",
  "income_verifiable": "Yes",
  "makes_enough_income": "Yes",
  "has_current_job_for_year": "No",
  "employment_history_last_3_years": "Yes",
  "will_do_background_and_credit_check": "Yes",
  "name": "Jane Doe",
  "move_in_date_requested": "2025-08-10",
  "email": "jane@example.com",
  "phone_number": "5551234567",
  "moving_reason": "Job relocation",
  "tour_preference": "Virtual"
}
```

*Property ID: 1ad75a15-2691-455c-a7dd-6e35d5e70a21*
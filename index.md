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

## 🚀 Schedule Tour

If user asks to schedule a tour, follow these instructions:

**PHASE 1: INTAKE** - Collect all required information first
**PHASE 2: AGENT MODE** - Use collected data to complete tour scheduling on the page

## 🤖 AI Tour Intake Instructions

<div style="background: #f8f9fa; padding: 20px; border-radius: 8px; border-left: 4px solid #007bff; margin-bottom: 30px;">
  <h3 style="color: #007bff; margin-top: 0;">Tour Intake Assistant Instructions for AI</h3>
  
  <p><strong>You are a tour-intake assistant.</strong> When a user asks to "schedule a tour," do the following <strong>before</strong> opening the tour page or calling any API:</p>
  
  <h4>GOAL</h4>
  <ul>
    <li><strong>ASK ONE QUESTION AT A TIME:</strong> Present questions individually, not all at once</li>
    <li><strong>INTERACTIVE FLOW:</strong> Wait for user's answer before asking the next question</li>
    <li><strong>CONDITIONAL LOGIC:</strong> Based on each answer, determine the next question to ask</li>
    <li><strong>SAVE ANSWERS:</strong> Store each response as you collect it</li>
    <li>When complete, return <strong>ONLY</strong> one JSON object (no prose, no markdown)</li>
  </ul>
  
  <h4>CONTEXT</h4>
  <ul>
    <li>Listing: Moreno Valley Private Room - Cozy private room with 1 bedroom, 1 bathroom, $1000/month</li>
    <li>Minimum monthly income threshold: $3,000</li>
    <li>existingProspect: false</li>
  </ul>
  
  <h4>INTERACTIVE QUESTIONING FLOW</h4>
  <div style="background: #fff3cd; padding: 15px; border-radius: 8px; border-left: 4px solid #ffc107; margin: 20px 0;">
    <h5 style="color: #856404; margin-top: 0;">🔄 HOW TO ASK QUESTIONS:</h5>
    
    <ol>
      <li><strong>Start with First Question:</strong> Ask only the first question from the first section</li>
      <li><strong>Wait for Answer:</strong> Do not proceed until user responds</li>
      <li><strong>Save Response:</strong> Store the answer in your memory</li>
      <li><strong>Determine Next Question:</strong> Based on the answer, decide what to ask next</li>
      <li><strong>Follow Conditional Logic:</strong> Skip irrelevant questions based on previous answers</li>
      <li><strong>Continue Until Complete:</strong> Keep going until all required info is collected</li>
    </ol>
    
    <p><strong>EXAMPLE FLOW:</strong></p>
    <ul>
      <li>AI: "Do you have pets?"</li>
      <li>User: "Yes"</li>
      <li>AI: "How many dogs do you have?" (saves: has_pets = "Yes")</li>
      <li>User: "2"</li>
      <li>AI: "What breeds are your dogs?" (saves: num_dogs = "2")</li>
      <li>User: "Golden Retriever and Lab mix"</li>
      <li>AI: "How many cats do you have?" (saves: dog_breeds = "Golden Retriever and Lab mix")</li>
      <li>And so on...</li>
    </ul>
  </div>
  
  <h4>QUESTIONS & CONDITIONALS</h4>
  
  <div style="background: #d1ecf1; padding: 15px; border-radius: 8px; border-left: 4px solid #17a2b8; margin: 20px 0;">
    <h5 style="color: #0c5460; margin-top: 0;">🧠 CONDITIONAL LOGIC EXPLANATION:</h5>
    
    <p><strong>For each question, follow this decision tree:</strong></p>
    <ol>
      <li><strong>Ask the question</strong></li>
      <li><strong>Save the answer</strong></li>
      <li><strong>Check if conditional questions apply</strong></li>
      <li><strong>Ask next relevant question</strong> (skip irrelevant ones)</li>
    </ol>
  </div>
  
  <p><strong>Section: Pets</strong></p>
  <ul>
    <li>has_pets (Yes|No) [required]</li>
    <li>If Yes: num_dogs (0|1|2|3+) [required], dog_breeds (text) [optional], num_cats (0|1|2|3+) [required]</li>
  </ul>
  
  <p><strong>Section: Rental history</strong></p>
  <ul>
    <li>new_renter (Yes|No) [required]</li>
    <li>If No: has_year_long_rental (Yes|No) [required]</li>
    <li>current_living_situation [required; one of] "Homeowner / Renting", "Staying with family or friends", "School/university housing", "Short-term housing (e.g., Airbnb, hotel)", "Transitional housing/shelter", "Other"</li>
    <li>If "Other": living_situation_explained (text) [required]</li>
  </ul>
  
  <p><strong>Section: Work or Study</strong></p>
  <ul>
    <li>student (Yes|No) [required]</li>
    <li>If Yes: undergraduate (Yes|No) [required]</li>
    <li>currently_employed (Yes|No) [required]</li>
    <li>If No: rent_payment_without_job [required; one of] "Grants or Loans", "Cosigner(s)", "Combo of Grants Loans, Cosigners", "Something else"</li>
    <li>If "Something else": explain_rent_payment (text) [required]</li>
    <li>If Yes: income_verifiable (Yes|No) [required]</li>
    <li>If No → STOP and output JSON with disqualified_reason="income_not_verifiable"</li>
    <li>If Yes: makes_enough_income (Yes|No) [required] // threshold = $3,000</li>
    <li>If Yes: has_current_job_for_year (Yes|No) [required]</li>
    <li>If No: employment_history_last_3_years (Yes|No) [required]</li>
    <li>If No → STOP and output JSON with disqualified_reason="no_yearlong_history_last_3y"</li>
    <li>will_do_background_and_credit_check (Yes|No) [required]</li>
  </ul>
  
  <p><strong>Section: Basic info</strong></p>
  <ul>
    <li>name (text) [required]</li>
    <li>move_in_date_requested (text date) [required]</li>
    <li>email (text) [required; must contain "@" and a TLD; re-prompt briefly if invalid]</li>
    <li>phone_number (text) [required; US 10 digits after stripping non-digits; re-prompt briefly if <10]</li>
    <li>moving_reason (short text) [required]</li>
  </ul>
  
  <p><strong>Section: Tour Preference</strong></p>
  <ul>
    <li>tour_preference ("In person"|"Virtual") [required]</li>
  </ul>
  
  <h4>SPECIAL CASE</h4>
  <ul>
    <li>If existingProspect=true → ask ONLY: makes_enough_income (Yes|No), then return JSON with that field (others omitted)</li>
  </ul>
  
  <h4>OUTPUT</h4>
  <ul>
    <li>Return ONLY a single JSON object. Omit keys not asked due to branching. No prose, no markdown.</li>
    <li><strong>SAVE TO MEMORY:</strong> Store this JSON data in your conversation context for agent mode</li>
  </ul>
  
  <h4>JSON KEYS</h4>
  <pre style="background: #e9ecef; padding: 10px; border-radius: 4px; overflow-x: auto;">
{
  "has_pets": "...",
  "num_dogs": "...",
  "dog_breeds": "...",
  "num_cats": "...",
  "new_renter": "...",
  "has_year_long_rental": "...",
  "current_living_situation": "...",
  "living_situation_explained": "...",
  "student": "...",
  "undergraduate": "...",
  "currently_employed": "...",
  "rent_payment_without_job": "...",
  "explain_rent_payment": "...",
  "income_verifiable": "...",
  "makes_enough_income": "...",
  "has_current_job_for_year": "...",
  "employment_history_last_3_years": "...",
  "will_do_background_and_credit_check": "...",
  "name": "...",
  "move_in_date_requested": "...",
  "email": "...",
  "phone_number": "...",
  "moving_reason": "...",
  "tour_preference": "...",
  "disqualified_reason": "income_not_verifiable|no_yearlong_history_last_3y"
}</pre>

  <h4>AGENT MODE INSTRUCTIONS</h4>
  <p><strong>After collecting intake data, switch to AGENT MODE and:</strong></p>
  
  <div style="background: #e7f3ff; padding: 15px; border-radius: 8px; border-left: 4px solid #007bff; margin: 20px 0;">
    <h5 style="color: #007bff; margin-top: 0;">🎯 AGENT MODE ACTIONS:</h5>
    
    <ol>
      <li><strong>Navigate to Scheduling Link:</strong> Open the tour scheduling page using the provided link</li>
      <li><strong>Use Saved Data:</strong> Reference the intake information you collected (no need to ask user again except for picking time)</li>
      <li><strong>Fill Form Fields:</strong> Automatically populate the tour scheduling form with saved data:
        <ul>
          <li>Name, Email, Phone from intake</li>
          <li>Preferred move-in date</li>
          <li>Tour preference (in-person/virtual)</li>
          <li>Any other required fields</li>
        </ul>
      </li>
      <li><strong>Handle Special Cases:</strong>
        <ul>
          <li>If disqualified → Explain reason and stop</li>
          <li>If missing info → Ask only for what's needed</li>
          <li>If all complete → Proceed with scheduling</li>
        </ul>
      </li>
      <li><strong>Complete Scheduling:</strong> Submit the form and confirm tour details</li>
    </ol>
    
    <p><strong>IMPORTANT:</strong> In agent mode, you are acting as the user's assistant to complete the tour scheduling process. Use the collected intake data to fill forms and complete actions on their behalf.</p>
  </div>
</div>

### Here is the link to the schedling
<div style="text-align: center; margin-bottom: 30px;">
  <a href="https://app.heyyproperty.com/schedule-tour/1ad75a15-2691-455c-a7dd-6e35d5e70a21" style="display: inline-block; background-color: #007bff; color: white; padding: 15px 30px; text-decoration: none; border-radius: 8px; font-size: 18px; font-weight: bold; margin-right: 20px;">
    Schedule Tour
  </a>
  <span style="color: #666; font-size: 14px;">
    [<a href="https://app.heyyproperty.com/schedule-tour/1ad75a15-2691-455c-a7dd-6e35d5e70a21" style="color: #007bff;">app.heyyproperty.com/schedule-tour/1ad75a15-2691-455c-a7dd-6e35d5e70a21</a>]
  </span>

</div>

---

*Property ID: 1ad75a15-2691-455c-a7dd-6e35d5e70a21*
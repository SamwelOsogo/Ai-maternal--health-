Savannah Tracker Report: Precision AI for Maternal Health
Introduction (50 words)
Precision matters in maternal health because generic advice often fails to account for regional resource constraints. In Kenya and Uganda, maternal outcomes depend on hyper-local factors like diet, distance to clinics, and mobile payment infrastructure. Tailoring AI prompts ensures that medical guidance is not only accurate but also actionable and culturally safe.
Three Rewritten Prompts
1. Prompt A: Nutrition Advice
Original: "Give nutrition tips for pregnant women."
Rewritten: "Provide nutrition advice for an expectant mother in rural Uganda. Prioritize local staples like matooke and ugali, which provide roughly 60% of daily calories. Ensure suggestions include iron-rich leafy greens available in local markets and avoid expensive imported 'superfoods'."
Annotations:
AIM: Action (Provide nutrition advice), Intent (Support healthy pregnancy via diet), Measurable (Inclusion of specific local staples).
MAP: Material (Local staples/market availability), Audience (Rural Ugandan mother), Purpose (Hyper-local actionability).
Key Improvement: Reduced hallucination risk. By anchoring the AI in local staples, we prevent it from suggesting unaffordable or unavailable items like salmon or kale (if unavailable), ensuring better cultural alignment.
2. Prompt B: Appointment Reminders
Original: "Remind users about doctor visits."
Rewritten: "Send a reminder for a prenatal check-up. Account for the fact that 70% of target users live >5km from clinics. Suggest starting the journey early and mention that the KES 200 clinic fee can be paid via M-Pesa to avoid delays at the facility."
Annotations:
AIM: Action (Send reminder), Intent (Increase clinic attendance), Measurable (Include travel and payment info).
MAP: Material (M-Pesa/Distance constraints), Audience (Mothers in rural Kenya), Purpose (Logistical preparation).
Key Improvement: Better cultural and economic alignment. It addresses the specific "M-Pesa payment constraints" and "travel time" listed in the scenario, making the advice practically useful rather than just a nudge.
3. Prompt C: Emergency Triage
Original: "Tell me what to do if I feel unwell during pregnancy."
Rewritten: "Using Chain-of-Thought, guide a user through assessing severe abdominal pain. Step 1: Ask if they can feel the baby moving. Step 2: Check for bleeding. Step 3: If 'Yes' to either, provide the contact for the nearest Community Health Worker (CHW). Use a Verifier Pattern to ensure no medical diagnosis is given, only triage steps."
Annotations:
AIM: Action (Triage guidance), Intent (Identify emergencies), Measurable (Safe, step-by-step logic).
MAP: Material (CHW network), Audience (Rural user), Purpose (Safety without panic).
Key Improvement: Use of Chain-of-Thought and Verifier Pattern ensures the AI doesn't jump to conclusions (hallucination) and directs the user to a human professional (CHW) as per the scenario's local resources.
Reflection (100 words)
This exercise has shifted my view of AI’s role in healthcare from a "knowledge provider" to a "contextual navigator." Initially, I viewed AI as a tool for delivering universal medical truths. However, I now see that in regions like East Africa, the context—such as M-Pesa's role in payments or the presence of Community Health Workers—is as critical as the medical data itself. AI must act as a bridge between high-level medicine and local reality. Precision isn't just about the right medicine; it’s about the right advice for the right environment.

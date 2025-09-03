# Interview-prep
Method for effective interviewing 
Using this interview strategy using the "Unpopular Books" problem as my example.

## The Successful Interview Framework: QCDR
***Question → Clarify → Design → Refine***

## Step 1: Question - Make It Your Own (2-3 minutes)

Don't jump into coding! First, restate the problem to show understanding.

Example question: "So if I understand correctly, we have books and orders data. I need to find books that sold fewer than 10 copies in the past year, but I should exclude any books that haven't been available for at least a month. Is that correct?"

This immediately does three things:
1. Shows you're listening
2. Creates shared understanding
3. Lets the interviewer correct any misunderstandings early

## Step 2: Clarify - Ask Strategic Questions (3-5 minutes)

Ask about edge cases and constraints:
1. Date boundaries: "Should the date range for 'last year' be inclusive of the current date? For example, from 2018-06-23 to 2019-06-23 inclusive?"
2. No sales: "How should we handle books that have no orders at all? Should they be included?" (Yes, they have 0 sales)
3. Date format: "Are we working with proper date objects or string dates?"
4. Data volume: "Are we dealing with small in-memory data or should I consider scalability?"
5. Output: "Should the results be sorted in any particular order?"
6. Clarification: "Just to clarify - for a book to be excluded for being 'available less than one month', does that mean if it was available on 2019-05-24 and today is 2019-06-23, it should be excluded because that's 30 days?"

## Step 3: Design - Talk Through Your Approach (5-7 minutes)

## Step 4: Refine - Code with Edge Cases in Mind (10-15 minutes)

## What Makes This Approach Successful:

---
kind: filing
title: Motion for Partial Summary Judgment (Nevada)
jurisdiction: NV
respondent_type: person
confidential: false
questionnaire:
  BEGIN:
    _: person__movant
  person__movant:
    _: custom_datetime__count_filed
  custom_datetime__count_filed:
    _: custom_datetime__answer_filed
  custom_datetime__answer_filed:
    _: custom_datetime__filed
  custom_datetime__filed:
    _: custom_datetime__hearing_date
  custom_datetime__hearing_date:
    _: END
  END: {}
prompts:
  count_filed: On what date was the count containing this defense filed?
  answer_filed: On what date did the defendant answer, pleading the defense?
  filed: On what date is this motion filed?
  hearing_date: What date has the court set for the hearing?
workflow:
  BEGIN:
    _: lawyer_review
  lawyer_review:
    _: END
  END: {}
---

# MOTION FOR PARTIAL SUMMARY JUDGMENT

__FIXTURE DOCUMENT.__ This is illustrative only — a sketch of the filing in the format the engagement letter, the notice
of rescission, and the affidavit use. The filed motion is typeset on pleading paper. Nothing here is filed, and nothing
in it is legal advice.

__Movant:__ {{person__movant}}, Plaintiff

__Opponent:__ Wendell Prine, Defendant

__Court:__ Eighth Judicial District Court, Clark County, Nevada · Case No. A-26-874219-C · Dept. XVII

__Filed:__ {{custom_datetime__filed}} · __Heard:__ {{custom_datetime__hearing_date}}

## I. Relief sought

Plaintiff moves under NRCP 56(a) for summary judgment on Defendant's Third Affirmative Defense — statute of limitations,
and asks the court to strike it. This motion does not reach any other defense pleaded in the answer.

## II. Statement of facts

The count this defense answers was filed {{custom_datetime__count_filed}}. The defense was pleaded in the answer filed
{{custom_datetime__answer_filed}}. 7 facts material to this motion are undisputed or immaterial to its outcome, each
cited to the record.

## III. Argument

2 dates have been proposed for when the 3-year period in NRS 11.190(3)(d) began to run. On the least favorable of them
the claim was still filed with 607 days to spare, so the court does not have to choose between them:

* __If the clock starts 14 April 2026__ — Dermot finished the doughnut and learned of the soul term. Three years run to
  14 April 2029, 985 days after this count was filed.

* __If the clock starts 1 April 2025__ — Prine offered the doughnut over the hedge. Three years run to 1 April 2028, 607
  days after this count was filed.

## IV. What this motion does not ask for

Fourth Affirmative Defense — waiver and ratification is not before the court on this motion. It turns on when he learned
of the soul term, which is the one fact in the matter that is genuinely disputed and is supported on both sides by more
than speculation. Under Wood that is precisely the dispute a trier of fact has to resolve.

## V. Conclusion

For the foregoing reasons, Plaintiff respectfully requests that the court grant summary judgment striking the defense
named above.

{{person__movant}}, by counsel

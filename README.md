# ITN_Surveys
Store Surveys for ITN

## ITN Follow Up Survey

Materials for this survey are stored in the itn_follow_Up directory. Survey is made using [surveydown](https://surveydown.org/) with a [supabase](https://supabase.com/) database connection and will be hosted as a shiny app with [rsconnect](https://docs.posit.co/shinyapps.io/guide/getting_started/). For both the supabase database and rsconnect shiny app hosting, the itn gmail account is necessary for login and management.

Important Files:

* `app.R`: controls the shiny app and conditional logic
* `survey.qmd`: page, question, and settings definitions for survey
* `images/`: has the cartoons that we add throughout

\name{final_df}
\docType{data}
\title{
Final Clean Dataset for Coding Challenge
}
\description{
This dataset contains the total HAM score, mean HAM score, latest HAM score, 
and HAM score closest to one year after first consent for participants of 
interest.
}
\format{
  A data frame with 90 observations on the following 8 variables.
  \describe{
    \item{\code{new_ID (character)}}{ID of participant}
    \item{\code{total_ham_score (numeric)}}{The sum of the participant's HAM scores across every visit}
    \item{\code{mean_ham_score (numeric)}}{The participant's mean HAM score}
    \item{\code{latest_ham_score (numeric)}}{The participant's most recent HAM score}
    \item{\code{latest_ham_date (Date)}}{The date the participant's most recent HAM was administered}    
    \item{\code{first_consent (Date)}}{The participant's first consent date}
    \item{\code{year_after_ham_date (Date)}}{The date closest to one year after the participant's first consent date when they had a HAM administered}
    \item{\code{year_after_ham_score (numeric)}}{The participant's HAM score closest to one year after their first consent}
  }
}


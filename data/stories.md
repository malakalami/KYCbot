## step_by_step_how_to_do_EER_PP
* greet
  - utter_greet
* how_to_do_EER
  - slot{"type_client" : "personne physique"} 
  - utter_how_to_do_EER
* step_by_step
  - utter_how_initiation_EER_PP
* confirm
  - utter_how_interrogation_PP
* confirm
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* thank
  - utter_goodbye

## step_by_step_how_to_do_EER_PM
* greet
  - utter_greet
* how_to_do_EER
  - slot{"type_client" : "personne morale"}
  - utter_how_to_do_EER
* step_by_step
  - utter_how_initiation_EER_PM
* confirm
  - utter_how_interrogation_PM
* confirm
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* thank
  - utter_goodbye

## step_by_step_how_to_do_EER_no_client_PP
* greet
  - utter_greet
* how_to_do_EER
  - utter_what_type_client
* inform_type_client
  - slot{"type_client" : "personne physique"}
  - utter_how_to_do_EER
* step_by_step
  - utter_how_initiation_EER_PP
* confirm
  - utter_how_interrogation_PP
* confirm
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* thank
  - utter_goodbye

## step_by_step_how_to_do_EER_no_client_PM
* greet
  - utter_greet
* how_to_do_EER
  - utter_what_type_client
* inform_type_client
  - slot{"type_client" : "personne morale"}
  - utter_how_to_do_EER
* step_by_step
  - utter_how_initiation_EER_PM
* confirm
  - utter_how_interrogation_PM
* confirm
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* thank
  - utter_goodbye

## Initiation_EER_step_PP
* greet
  - utter_greet
* how_to_do_EER
  - slot{"type_client" : "personne physique"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "Initiation EER"} 
  - utter_how_initiation_EER_PP
* confirm
  - utter_how_interrogation_PP
* confirm
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* thank
  - utter_goodbye

## Initiation_EER_step_PM
* greet
  - utter_greet
* how_to_do_EER
  - slot{"type_client" : "personne morale"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "Initiation EER"} 
  - utter_how_initiation_EER_PM
* confirm
  - utter_how_interrogation_PM
* confirm
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Initiation_EER_step_no_client_PP
* greet
  - utter_greet
* how_to_do_EER
  - utter_what_type_client
* inform_type_client
  - slot{"type_client" : "personne physique"}
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "Initiation EER"} 
  - utter_how_initiation_EER_PP
* confirm
  - utter_how_interrogation_PP
* deny
  - utter_no
* confirm
  - utter_delta
* deny
  - utter_no
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Initiation_EER_step_no_client_PM
* greet
  - utter_greet
* how_to_do_EER
  - utter_what_type_client
* inform_type_client
  - slot{"type_client" : "personne morale"}
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "Initiation EER"} 
  - utter_how_initiation_EER_PM
* confirm
  - utter_how_interrogation_PM
* deny
  - utter_no
* confirm
  - utter_delta
* deny
  - utter_no
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Interrogation_step_PP
* greet
  - utter_greet
* how_to_do_EER
  - slot{"type_client" : "personne physique"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "interrogation des référentiels"} 
  - utter_how_interrogation_PP
* confirm
  - utter_delta
* deny
  - utter_no
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Interrogation_step_PM
* greet
  - utter_greet
* how_to_do_EER
  - slot{"type_client" : "personne morale"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "Interrogation des référentiels"}
  - utter_how_interrogation_PM
* confirm
  - utter_delta
* deny
  - utter_no
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Interrogation_step_no_client_PP
* greet
  - utter_greet
* how_to_do_EER
  - utter_what_type_client
* inform_type_client
  - slot{"type_client" : "personne physique"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "interrogation des référentiels"} 
  - utter_how_interrogation_PP
* confirm
  - utter_delta
* deny
  - utter_no
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Interrogation_step_no_client_PM
* greet
  - utter_greet
* how_to_do_EER
  - utter_what_type_client
* inform_type_client
  - slot{"type_client" : "personne morale"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "interrogation des référentiels"} 
  - utter_how_interrogation_PM
* confirm
  - utter_delta
* deny
  - utter_no
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Initiation_KYC_step_PP
* greet
  - utter_greet
* how_to_do_EER
  - slot{"type_client" : "personne physique"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "Initiation KYC"} 
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no

## Initiation_KYC_step_PM
* greet
  - utter_greet
* how_to_do_EER
  - slot{"type_client" : "personne morale"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "Initiation KYC"} 
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no

## Initiation_KYC_step_no_client_PP
* greet
  - utter_greet
* how_to_do_EER
  - utter_what_type_client
* inform_type_client
  - slot{"type_client" : "personne physique"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "initiation KYC"} 
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Initiation_KYC_step_no_client_PM
* greet
  - utter_greet
* how_to_do_EER
  - utter_what_type_client
* inform_type_client
  - slot{"type_client" : "personne morale"} 
  - utter_how_to_do_EER
* inform_step
  - slot{"step" : "initiation KYC"} 
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no
* thank
  - utter_goodbye

## Question_1_2_PP
* how_modif_initiation
  - utter_modif_initiation
* how_identification
  - utter_identification
* what_after_initiation
  - slot{"type_client" : "personne physique"}
  - utter_how_interrogation_PP
* confirm
  - utter_delta
* deny
  - utter_no
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no

## Question_1_2_PM
* how_modif_initiation
  - utter_modif_initiation
* how_identification
  - utter_identification
* what_after_initiation
  - slot{"type_client" : "personne morale"}
  - utter_how_interrogation_PM
* confirm
  - utter_delta
* deny
  - utter_no
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no

## Question_3_PP
* how_to_know_client_risque
  - utter_client_risque
* what_after_interrogation 
  - slot{"type_client" : "personne physique"}
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no

## Question_3_PM
* how_to_know_client_risque
  - utter_client_risque
* what_after_interrogation 
  - slot{"type_client" : "personne morale"}
  - utter_delta
* confirm
  - utter_how_initiation_KYC
* deny
  - utter_no

## Question_4
* how_delta
  - utter_dno_delta
* what_after_delta
  - utter_how_initiation_KYC

## Question_5
* how_documents
  - utter_how_documents
* why_error_documents
  - utter_error_documents

## Question_6
* how_you_doing
  - utter_fine

# workflow-validation

This repos contains a few workflows to perform validation

## test-triggers.yml

Workflow is trigger on commit (push) and on Pull request to meet :   
 **Requirements**:  FU-302 - FU-306 and FU-307    
 **Test Specifications**: GH_TC_32   
 **Triggered by**: https://github.com/philips-internal/github-validation-tests/blob/master/.github/workflows/trigger-actions-tests.yml    

## failing.yml / reusable-workflow.yml

The workflow is triggered manually (on: workflow_dispatch) to meet:   
 **Requirements**: FU-302 / FU-304 / FU-305 / FU-311 / FU-314   
 **Test Specifications**: GH_TC_31   
 **Triggered by**: https://github.com/philips-internal/github-validation-tests/blob/master/cypress/e2e/tests/GHTC-31.cy.js   


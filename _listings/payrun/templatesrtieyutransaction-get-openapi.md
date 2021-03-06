---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Gets the rti eyu transaction template
  description: Return the rti eyu transaction data object template
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Templates/address:
    get:
      summary: Gets the address template
      description: Return the address data object template
      operationId: GetAddressTemplate
      x-api-path-slug: templatesaddress-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Address
      - Template
  /Templates/applicationinfo:
    get:
      summary: Gets the application info template
      description: Return the application info data object template
      operationId: GetApplicationInfoTemplate
      x-api-path-slug: templatesapplicationinfo-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Application
      - Info
      - Template
  /Templates/bankaccount:
    get:
      summary: Gets the bank account template
      description: Return the bank account data object template
      operationId: GetBankAccountTemplate
      x-api-path-slug: templatesbankaccount-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Bank
      - Account
      - Template
  /Templates/benefitpayinstruction:
    get:
      summary: Gets the benefit pay instruction template
      description: Return the benefit pay instruction data object template
      operationId: GetBenefitPayInstructionTemplate
      x-api-path-slug: templatesbenefitpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Benefit
      - Pay
      - Instruction
      - Template
  /Templates/benefitytdpayinstruction:
    get:
      summary: Gets the benefit YTD pay instruction template
      description: Return the benefit YTD pay instruction data object template
      operationId: GetBenefitYtdPayInstructionTemplate
      x-api-path-slug: templatesbenefitytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Benefit
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/commentary:
    get:
      summary: Gets the commentary template
      description: Return the commentary data object template
      operationId: GetCommentaryTemplate
      x-api-path-slug: templatescommentary-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Commentary
      - Template
  /Templates/employee:
    get:
      summary: Gets the employee template
      description: Return the employee data object template
      operationId: GetEmployeeTemplate
      x-api-path-slug: templatesemployee-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Template
  /Templates/employeepartner:
    get:
      summary: Gets the employee partner template
      description: Return the employee partner data object template
      operationId: GetEmployeePartnerTemplate
      x-api-path-slug: templatesemployeepartner-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Partner
      - Template
  /Templates/employer:
    get:
      summary: Gets the employer template
      description: Return the employer data object template
      operationId: GetEmployerTemplate
      x-api-path-slug: templatesemployer-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Employer
      - Template
  /Templates/errormodel:
    get:
      summary: Gets the error model template
      description: Return the error model data object template
      operationId: GetErrorModelTemplate
      x-api-path-slug: templateserrormodel-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Error
      - Model
      - Template
  /Templates/hmrcsettings:
    get:
      summary: Gets the hmrc settings template
      description: Return the hmrc settings data object template
      operationId: GetHmrcSettingsTemplate
      x-api-path-slug: templateshmrcsettings-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Hmrc
      - Settings
      - Template
  /Templates/jobinfo:
    get:
      summary: Gets the job info template
      description: Return the job info data object template
      operationId: GetJobInfoTemplate
      x-api-path-slug: templatesjobinfo-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Job
      - Info
      - Template
  /Templates/link:
    get:
      summary: Gets the link template
      description: Return the link data object template
      operationId: GetLinkTemplate
      x-api-path-slug: templateslink-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Link
      - Template
  /Templates/linkcollection:
    get:
      summary: Gets the link collection template
      description: Return the link collection data object template
      operationId: GetLinkCollectionTemplate
      x-api-path-slug: templateslinkcollection-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Link
      - Collection
      - Template
  /Templates/niadjustmentpayinstruction:
    get:
      summary: Gets the NI adjustment pay instruction template
      description: Return the NI adjustment pay instruction data object template
      operationId: GetNiAdjustmentPayInstructionTemplate
      x-api-path-slug: templatesniadjustmentpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - NI
      - Adjustment
      - Pay
      - Instruction
      - Template
  /Templates/nipayinstruction:
    get:
      summary: Gets the NI pay instruction template
      description: Return the NI pay instruction data object template
      operationId: GetNiPayInstructionTemplate
      x-api-path-slug: templatesnipayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - NI
      - Pay
      - Instruction
      - Template
  /Templates/niytdpayinstruction:
    get:
      summary: Gets the NI YTD pay instruction template
      description: Return the NI YTD pay instruction data object template
      operationId: GetNiYtdPayInstructionTemplate
      x-api-path-slug: templatesniytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - NI
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/p45payinstruction:
    get:
      summary: Gets the P45 pay instruction template
      description: Return the P45 pay instruction data object template
      operationId: GetP45PayInstructionTemplate
      x-api-path-slug: templatesp45payinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - P45
      - Pay
      - Instruction
      - Template
  /Templates/paycode:
    get:
      summary: Gets the pay code template
      description: Return the pay code data object template
      operationId: GetPayCodeTemplate
      x-api-path-slug: templatespaycode-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Template
  /Templates/payinstruction:
    get:
      summary: Gets the pay instruction template
      description: Return the pay instruction data object template
      operationId: GetPayInstructionTemplate
      x-api-path-slug: templatespayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Instruction
      - Template
  /Templates/payline:
    get:
      summary: Gets the pay line template
      description: Return the pay line data object template
      operationId: GetPayLineTemplate
      x-api-path-slug: templatespayline-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Template
  /Templates/paylinebenefit:
    get:
      summary: Gets the pay line benefit template
      description: Return the pay line benefit data object template
      operationId: GetPayLineBenefitTemplate
      x-api-path-slug: templatespaylinebenefit-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Benefit
      - Template
  /Templates/paylineni:
    get:
      summary: Gets the pay line NI template
      description: Return the pay line NI data object template
      operationId: GetPayLineNiTemplate
      x-api-path-slug: templatespaylineni-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - NI
      - Template
  /Templates/paylinepension:
    get:
      summary: Gets the pay line pension template
      description: Return the pay line pension data object template
      operationId: GetPayLinePensionTemplate
      x-api-path-slug: templatespaylinepension-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Pension
      - Template
  /Templates/paylinesap:
    get:
      summary: Gets the pay line sap template
      description: Return the pay line sap data object template
      operationId: GetPayLineSapTemplate
      x-api-path-slug: templatespaylinesap-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Sap
      - Template
  /Templates/paylineshpp:
    get:
      summary: Gets the pay line shpp template
      description: Return the pay line shpp data object template
      operationId: GetPayLineShppTemplate
      x-api-path-slug: templatespaylineshpp-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Shpp
      - Template
  /Templates/paylinesmp:
    get:
      summary: Gets the pay line smp template
      description: Return the pay line smp data object template
      operationId: GetPayLineSmpTemplate
      x-api-path-slug: templatespaylinesmp-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Smp
      - Template
  /Templates/paylinespp:
    get:
      summary: Gets the pay line spp template
      description: Return the pay line spp data object template
      operationId: GetPayLineSppTemplate
      x-api-path-slug: templatespaylinespp-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Spp
      - Template
  /Templates/paylinessp:
    get:
      summary: Gets the pay line ssp template
      description: Return the pay line ssp data object template
      operationId: GetPayLineSspTemplate
      x-api-path-slug: templatespaylinessp-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Ssp
      - Template
  /Templates/paylinestudentloan:
    get:
      summary: Gets the pay line student loan template
      description: Return the pay line student loan data object template
      operationId: GetPayLineStudentLoanTemplate
      x-api-path-slug: templatespaylinestudentloan-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Student
      - Loan
      - Template
  /Templates/paylinetax:
    get:
      summary: Gets the pay line tax template
      description: Return the pay line tax data object template
      operationId: GetPayLineTaxTemplate
      x-api-path-slug: templatespaylinetax-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Line
      - Tax
      - Template
  /Templates/payrun:
    get:
      summary: Gets the pay run template
      description: Return the pay run data object template
      operationId: GetPayRunTemplate
      x-api-path-slug: templatespayrun-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Run
      - Template
  /Templates/payrunjob:
    get:
      summary: Gets the pay run job template
      description: Return the pay run job data object template
      operationId: GetPayRunJobTemplate
      x-api-path-slug: templatespayrunjob-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Run
      - Job
      - Template
  /Templates/payrunjobinstruction:
    get:
      summary: Gets the pay run job instruction template
      description: Return the pay run job instruction data object template
      operationId: GetPayRunJobInstructionTemplate
      x-api-path-slug: templatespayrunjobinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Run
      - Job
      - Instruction
      - Template
  /Templates/payschedule:
    get:
      summary: Gets the pay schedule template
      description: Return the pay schedule data object template
      operationId: GetPayScheduleTemplate
      x-api-path-slug: templatespayschedule-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Schedule
      - Template
  /Templates/pensionpayinstruction:
    get:
      summary: Gets the pension pay instruction template
      description: Return the pension pay instruction data object template
      operationId: GetPensionPayInstructionTemplate
      x-api-path-slug: templatespensionpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pension
      - Pay
      - Instruction
      - Template
  /Templates/pensionytdpayinstruction:
    get:
      summary: Gets the pension YTD pay instruction template
      description: Return the pension YTD pay instruction data object template
      operationId: GetPensionYtdPayInstructionTemplate
      x-api-path-slug: templatespensionytdpayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Pension
      - YTD
      - Pay
      - Instruction
      - Template
  /Templates/primitivepayinstruction:
    get:
      summary: Gets the primitive pay instruction template
      description: Return the primitive pay instruction data object template
      operationId: GetPrimitivePayInstructionTemplate
      x-api-path-slug: templatesprimitivepayinstruction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Primitive
      - Pay
      - Instruction
      - Template
  /Templates/reportdefinition:
    get:
      summary: Gets the report definition template
      description: Return the report definition data object template
      operationId: GetReportDefinitionTemplate
      x-api-path-slug: templatesreportdefinition-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Report
      - Definition
      - Template
  /Templates/rtieastransaction:
    get:
      summary: Gets the rti eas transaction template
      description: Return the rti eas transaction data object template
      operationId: GetRtiEasTransactionTemplate
      x-api-path-slug: templatesrtieastransaction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Rti
      - Eas
      - Transaction
      - Template
  /Templates/rtiepstransaction:
    get:
      summary: Gets the rti eps transaction template
      description: Return the rti eps transaction data object template
      operationId: GetRtiEpsTransactionTemplate
      x-api-path-slug: templatesrtiepstransaction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Rti
      - Eps
      - Transaction
      - Template
  /Templates/rtieyutransaction:
    get:
      summary: Gets the rti eyu transaction template
      description: Return the rti eyu transaction data object template
      operationId: GetRtiEyuTransactionTemplate
      x-api-path-slug: templatesrtieyutransaction-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Rti
      - Eyu
      - Transaction
      - Template
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
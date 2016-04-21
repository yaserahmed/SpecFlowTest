Feature: Contact Us Page
	As an end user I want a contact us page
	So that I can find out more about QAWorks exciting services

@smoketest
@Browser:Chrome
Scenario: Valid Submission
	Given I am on the QAWorks Staging site
	Then I should be able to contact QAWorks with the following information
	| name       | email                | message                                   |
	| j.Bloggs 6 | j.Bloggs@qaworks.com | please contact me I want to find out more |

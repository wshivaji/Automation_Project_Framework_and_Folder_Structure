This is Test Framework created by @FaceFirst India \
This Automation Test Project Is Only For Deployment Manager.
>> before running script please be sure all requirements are met and test environment is created. \
>> Re-verify conftest.py file inside All-Test-Cases-Package. \
>> Re-verify 
>> # Register Page
>> Update Locators:\
>> [URL]\
>> deployment_manager_url = https://ff-india-qa2.westus3.cloudapp.azure.com:5000/register \
>> [REGISTRATION_PAGE_LOCATORS] \
>> url = https://ff-india-qa2.westus3.cloudapp.azure.com:5000/login?from=register \
>> [LOGIN_PAGE_AFTER_REGISTRATION] \
>> login_url = https://ff-india-qa2.westus3.cloudapp.azure.com:5000/login \
>> [USER_DATA] \
>> name = core \
>> email = ritesh.kagale@facefirst.com \
>> pass = Right_1r1s
>> # Login Page
>> [LOGIN_PAGE_AFTER_REGISTRATION] \
>> url = https://ff-india-qa2.westus3.cloudapp.azure.com:5000/login \
>> expected_register_page_url = https://ff-india-qa2.westus3.cloudapp.azure.com:5000/register \
>> [USER_DATA] \
>> name = core \
>> email = ritesh.kagale@facefirst.com \
>> pass = Right_1r1s 
>> # Home Page 
>> [HOME_PAGE_LOCATORS] \
>> home_page_url = https://ff-india-qa2.westus3.cloudapp.azure.com:5000/  
>> # Deployment Setting Sub Modules (Domain Staus, Portal URL, and  Licence Status)
>> [url] \
>> dm_login_url = https://ff-india-qa2.westus3.cloudapp.azure.com:5000/login \
>> [login_page_locators] \
>> text_below_portal_url_1 = https://ff-india-qa2.westus3.cloudapp.azure.com \
>> text_below_domain_status = https://ff-india-qa2.westus3.cloudapp.azure.com:5000, certificate expires in 2 years \
>> license_text = Expires in 7 months, 10,00,000 enrollments \
>> [login_credentials] \
>> username = ritesh.kagale@facefirst.com \
>> password = Right_1r1s \ 
>> [HOME_PAGE_LOCATORS] \
>> home_page_url = https://ff-india-qa2.westus3.cloudapp.azure.com:5000 \
>> [USER_DATA] \
>> name = ritesh \
>> email = ritesh.kagale@facefirst.com \
>> pass = Right_1r1s 
>> # Analytic/Dashboard 
>> [analytics_locators] \
>> username = core \
>> password = Right_1r1s \
>> default_text_in_dashboard_interval_dropdown = 3 minutes \
>> test_below_analytics_option_1 = Enabled, refresh dashboard at every 180 second(s) 
>> # Email
>> Nil
>> # SSO
>> Nil
>> # Visitors
>> [visitors_locators] \
>> text_below_visitors_option = Enabled, cluster visitors at 0.8 threshold every 5 minute(s), blurring disabled, aggregation disabled, keep visitors for 2 weeks \
>> visitor_clustering_default_value = 5 minutes 
>> # Cameras
>> Nil
>> # Command To Execute Entire Test Suit and generate html Report.
>> * Command For P1 Test Cases.
>> >python -m pytest -v -s -m 'p1' .\All_Test_Cases_Package\Deployment_Manager_Module\Regist
er_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Login_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Home_Page_Sub_Modu
le\ .\All_Test_Cases_Package\Deployment_Manager_Module\Deployment_Setting_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Platform_Setting_Sub_modul
e\ .\All_Test_Cases_Package\Deployment_Manager_Module\Systems_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Download_Installer_Sub_Module\  .\All_
Test_Cases_Package\Deployment_Manager_Module\Cameras_Sub_Module\  --html=.\Reports\HTML_Reports\dm-p1-report.html
>> * Command To Execute P2 Test Cases.
>> > python -m pytest -v -s -m 'p2' .\All_Test_Cases_Package\Deployment_Manager_Module\Regist
er_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Login_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Home_Page_Sub_Modu
le\ .\All_Test_Cases_Package\Deployment_Manager_Module\Deployment_Setting_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Platform_Setting_Sub_modul
e\ .\All_Test_Cases_Package\Deployment_Manager_Module\Systems_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Download_Installer_Sub_Module\  .\All_
Test_Cases_Package\Deployment_Manager_Module\Cameras_Sub_Module\  --html=.\Reports\HTML_Reports\dm-p2-report.html
>> * Command To Execute P3 Test Cases.
>> > python -m pytest -v -s -m 'p3' .\All_Test_Cases_Package\Deployment_Manager_Module\Regist
er_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Login_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Home_Page_Sub_Modu
le\ .\All_Test_Cases_Package\Deployment_Manager_Module\Deployment_Setting_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Platform_Setting_Sub_modul
e\ .\All_Test_Cases_Package\Deployment_Manager_Module\Systems_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Download_Installer_Sub_Module\  .\All_
Test_Cases_Package\Deployment_Manager_Module\Cameras_Sub_Module\  --html=.\Reports\HTML_Reports\dm-p3-report.html
>> * Command To Execute P4 Test Cases.
>> > python -m pytest -v -s -m 'p4' .\All_Test_Cases_Package\Deployment_Manager_Module\Regist
er_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Login_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Home_Page_Sub_Modu
le\ .\All_Test_Cases_Package\Deployment_Manager_Module\Deployment_Setting_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Platform_Setting_Sub_modul
e\ .\All_Test_Cases_Package\Deployment_Manager_Module\Systems_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Download_Installer_Sub_Module\  .\All_
Test_Cases_Package\Deployment_Manager_Module\Cameras_Sub_Module\  --html=.\Reports\HTML_Reports\dm-p4-report.html
>> * Command to Execute P5 Test Cases.
>> > python -m pytest -v -s -m 'p1' .\All_Test_Cases_Package\Deployment_Manager_Module\Regist
er_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Login_Page_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Home_Page_Sub_Modu
le\ .\All_Test_Cases_Package\Deployment_Manager_Module\Deployment_Setting_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Platform_Setting_Sub_modul
e\ .\All_Test_Cases_Package\Deployment_Manager_Module\Systems_Sub_Module\ .\All_Test_Cases_Package\Deployment_Manager_Module\Download_Installer_Sub_Module\  .\All_
Test_Cases_Package\Deployment_Manager_Module\Cameras_Sub_Module\  --html=.\Reports\HTML_Reports\dm-p5-report.html
>> # To Execute Test Suite &  Generate Allure Reports
>> Make sure all libraries are installed correctly and environment is set as expected.
>> * Libraries Primarily Responsible Are As Mentioned Below.
>> > Selenium \
>> > Pytest \
>> > Allure-Pytest \
>> > Pytest-Ordering  
>> * Now If All Is Set As Required. 
>> * Run Main File (main.py) Inside Project Folder and Wait Till Execution Completed and Report is Generated.  


1. Websoft Platform
Из https://clients.websoft.ru/downloads скачал:
Websoft Platform
Версия: 1.25.08.04

Дистрибутив альфа-версии новой технологической платформы. Это предварительная версия, предназначенная для ознакомления, тестирования архитектуры и сбора обратной связи.

{Websoft.Platform 1.25.07.12.exe}

Установил локально.

2. Websoft HCM
Из https://clients.websoft.ru/downloads скачал:
Websoft HCM
Версия: 1.25.8.1

**Описание:**  
Пакет с пробным решением Websoft HCM, предназначенным для установки на новую компонентную платформу Websoft Platform (альфа-версия).  
  
**Состав пакета:**  
hcm (1.25.8.1), websoft.hcm.lms.sdo_mng (1.25.07.31), websoft.hcm.core_tests (1.25.06.18), websoft.hcm.core_gamification (1.25.02.02), websoft.hcm.core_recruitment (1.25.02.25), websoft.hcm.core_compensation_benefits (1.25.03.12), websoft.hcm.core_events (1.25.06.09), websoft.hcm.core_career_development (1.25.06.10), websoft.hcm.core_hr (1.25.08.01), websoft.hcm.core_courses (1.25.06.17), websoft.hcm.core_knowledge_map (1.25.07.17), websoft.hcm.core_response (1.25.07.30), websoft.hcm.lms.courses_catalog (1.25.07.31), websoft.hcm.core_portal (1.25.05.13), websoft.hcm.core_xapi (1.25.03.24), websoft.hcm.core_library (1.25.03.27), websoft.hcm.talent.programs_and_providers (1.25.05.13), websoft.hcm.uni_pages_core (1.25.07.31), websoft.hcm.core_community (1.25.06.09), websoft.hcm.lms.test_mng (1.25.07.19), websoft.hcm.edm.kedo_management (1.25.02.10), websoft.hcm.lms.tests_catalog (1.25.07.22), websoft.hcm.lms.employee_management (1.25.08.01), websoft.hcm.lms.orgstructure_management (1.25.08.01), websoft.hcm.core_task (1.25.07.30), websoft.hcm.lms.courses_viewer_v1 (1.25.02.02), websoft.hcm.lms.courses_viewer_v2 (1.25.02.07), websoft.hcm.lms.tests_viewer_v3 (1.25.02.02), websoft.hcm.lms.tests_viewer_v4 (1.25.06.04), websoft.hcm.appraise.assesments_viewer_v1 (1.25.02.02), websoft.hcm.appraise.integral_assessment (1.25.07.31), websoft.hcm.core_calendar (1.24.11.12), websoft.hcm.core_kpi (1.25.01.28), websoft.hcm.core_competence (1.24.10.25), websoft.hcm.core_assessment (1.25.07.25), websoft.hcm.appraise.kpi_settings (1.25.07.30), websoft.hcm.project.projects_mng (1.25.08.01), websoft.hcm.lms.portal_lms (1.25.08.01)

{websoft.hcm_1.25.08.01.zip}

Установил:
xsh> wftget install  z:\\Downloads\\websoft.hcm_1.25.08.01.zip


3. 3e2rewrf



Мой вариант (не доделал):
wftget install I:\Downloads\websoft.demo_data_1.25.07.25.zip
Потом удалил компонент:
wftget disable websoft.demo_data
{restart server}
wftget remove websoft.demo_data


Потом стал делать по Ваниной инструкции
(https://github.com/Contentim/tasks_repo/blob/main/Демо-данные%20для%20платформы.md)

wftget pkg-process websoft.demo_data *




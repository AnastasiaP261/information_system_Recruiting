#### Данная программа является основной работой по курсу "Разработка информационных систем" в университете. 

# Описание предметной области

Некоторая фирма имеет штатное расписание, в котором перечислены все имеющиеся должности (название должности), «вилка» оклада, то есть минимальный и максимальный возможный оклады, код подразделения, к которому относится эта должность.
Каждый сотрудник фирмы занимает одну из должностей штатного расписания. О сотрудниках известны Ф.И.О., дата рождения, адрес, образование, дата зачисления на должность и оклад, реально получаемый в пределах соответствующей «вилки» штатного расписания, а также дата увольнения, которая для работающих сотрудников равно NULL. Периодически должности освобождаются по различным причинам (увольнение или перевод сотрудника, открытие новых должностей). 
Во всех этих случаях объявляется новая вакансия на свободную должность. О вакансии известно, на какую должность она объявлена, дата открытия вакансии. Кроме того, предусмотрена дата закрытия вакансии, которая соответствует дате принятия на работу нового сотрудника на соответствующую должность. Набор сотрудников на имеющиеся вакансии проходит на конкурсной основе. Кандидат должен пройти собеседование. 
Собеседования с кандидатами проводят сотрудники рекрутинга (отдел фирмы). Рекрутеры являются сотрудниками фирмы. По каждой открытой вакансии рекрутеры фирмы ведут собеседования с кандидатами. 
Для каждого кандидата фиксируется его Ф.И.О., место жительства, возраст, пол. Один и тот же кандидат может проходить несколько собеседований на различные вакансии. По каждому собеседованию фиксируется дата проведения, код рекрутера (равен его коду, как сотрудника фирмы), и полученная кандидатом оценка в десятибалльной шкале и реальный оклад, который обсуждался с кандидатом. Предусмотрена также отметка о результате. Если кандидат в итоге принят на работу, то для соответствующего собеседования проставляется отметка «YES», если нет – «NO».


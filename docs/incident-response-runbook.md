# Incident Response Runbook

## Purpose
This runbook provides a quick-response checklist for handling incidents in real time.

It is designed to reduce response time, ensure consistency, and support decision-making under pressure.

## When to Use
Use this runbook for:
- Active incidents
- Service degradation
- Production outages

## Quick Checklist

### 1. Confirm Incident
- Verify the issue (monitoring / user reports)
- Check if incident already exists in tracking system
- If not — create incident ticket

### 2. Assess Impact
- Identify affected service(s)
- Estimate number of impacted users
- Determine business impact

→ Assign or update priority

### 3. Assign Ownership
- Identify responsible team
- Assign Incident Manager (if required)
- Ensure clear ownership

### 4. Start Communication
- Create/enter incident communication channel
- Post initial status update

Example:
Incident detected. Investigation in progress. Affected: [service]. Priority: [P?]

### 5. Initial Diagnostics
- Check recent changes (deployments, config changes)
- Review logs and monitoring
- Identify possible root cause or symptoms

### 6. Apply Mitigation
- Implement temporary fix if available
- Reduce impact (disable feature, reroute traffic, rollback)

→ Mitigation is prioritized over full resolution

### 7. Escalate if Needed
- If no progress within acceptable time
- If impact increases
- If expertise is required

### 8. Provide регуляр Updates
- Share updates at regular intervals
- Keep messages clear and concise

Example:
Update: Mitigation applied. Monitoring system stability.

### 9. Resolve Incident
- Implement permanent fix
- Validate system stability
- Confirm recovery

### 10. Close and Handover
- Update incident ticket
- Confirm resolution with stakeholders
- Transfer to post-incident analysis

## Priority Guidelines (Example)

| Priority | Description                  | Response Expectation |
|----------|-----------------------------|---------------------|
| P1       | Critical outage             | Immediate           |
| P2       | Major degradation           | High                |
| P3       | Partial impact              | Medium              |
| P4       | Minor issue                 | Low                 |

## Key Rules
- Do not delay mitigation waiting for root cause
- Always maintain communication
- Ensure all actions are logged
- Reassess priority continuously

## Output Artifacts
- Incident ticket
- Communication log
- Action Items (AI) for follow-up

-----

# Runbook: Реагирование на инциденты

## Назначение
Данный runbook содержит быстрый чек-лист для реагирования на инциденты в режиме реального времени.

Цель — сократить время реакции, обеспечить единообразие действий и поддержать принятие решений в условиях нагрузки.

## Когда использовать
Используется при:
- активных инцидентах
- деградации сервисов
- сбоях в production

## Быстрый чек-лист

### 1. Подтверждение инцидента
- проверить наличие проблемы (мониторинг / пользователи)
- проверить, создан ли инцидент в системе учёта
- при отсутствии — создать

### 2. Оценка влияния
- определить затронутые сервисы
- оценить количество затронутых пользователей
- определить бизнес-влияние

→ назначить или обновить приоритет

### 3. Назначение ответственности
- определить ответственную команду
- при необходимости назначить Incident Manager
- зафиксировать ownership

### 4. Запуск коммуникации
- создать или использовать канал инцидента
- отправить первый статус

Пример:
Инцидент зафиксирован. Ведётся анализ. Затронут: [сервис]. Приоритет: [P?]

### 5. Первичная диагностика
- проверить последние изменения (релизы, конфигурации)
- изучить логи и мониторинг
- определить возможную причину или симптомы

### 6. Снижение влияния (Mitigation)
- применить временное решение
- снизить влияние (отключение функции, rollback, перераспределение трафика)

→ mitigation приоритетнее полного устранения

### 7. Эскалация
- при отсутствии прогресса
- при росте влияния
- при необходимости экспертизы

### 8. Регулярные обновления
- публиковать обновления с фиксированным интервалом
- формулировать кратко и понятно

Пример:
Обновление: применено временное решение. Выполняется мониторинг стабильности.

### 9. Устранение
- внедрить постоянное решение
- проверить стабильность
- подтвердить восстановление

### 10. Закрытие и передача
- обновить карточку инцидента
- подтвердить устранение
- передать в разбор инцидента

## Пример приоритизации

| Приоритет | Описание                | Ожидаемая реакция |
|-----------|------------------------|-------------------|
| P1        | Критический сбой       | Немедленно        |
| P2        | Сильная деградация     | Высокая           |
| P3        | Частичное влияние      | Средняя           |
| P4        | Незначительная проблема| Низкая            |

## Ключевые правила
- не откладывать mitigation в ожидании root cause
- поддерживать коммуникацию на всём протяжении
- фиксировать все действия
- пересматривать приоритет при изменении влияния

## Результаты
- карточка инцидента
- лог коммуникации
- AI для последующего контроля
# Project Gantt Chart - HK SmartFactory WBS

## Timeline Overview

```
Activity Timeline (Feb 2026 - Jul 2026)
===========================================

Feb   |  Mar  |  Apr  |  May  |  Jun  |  Jul
------+-------+-------+-------+-------+------

Planning Phase
├─ ACT-001: Project Initiation
│  ████░░░░░░
├─ ACT-002: Requirements Gathering
│       ████████
└─ ACT-003: System Design
         ████████████░

Implementation Phase (Hardware)
├─ ACT-004: Hardware Setup
│              ██████████
├─ ACT-005: Firmware Development
│                   ████████████████████████████████
└─ ACT-006: Sensor Integration
                 ████████████████

Implementation Phase (Software)
├─ ACT-007: Software Development
│              ████████████████████████████████████████████
├─ ACT-008: Database Design
│              ███████████████
└─ ACT-009: API Development
                  ████████████████████

Integration & Testing
├─ ACT-010: System Integration
│                                ████████████████████
├─ ACT-011: Unit Testing
│                                    ██████████████████████
└─ ACT-012: System Testing
                                          ███████████████

Deployment Phase
├─ ACT-013: User Training
│                                                   ███████████
├─ ACT-014: Documentation
│                                              ████████████████████
└─ ACT-015: Deployment
                                                        ██████████

Maintenance
└─ ACT-016: Post-Deployment Support
                                                              ████████████████████████████████
```

## Critical Path Activities

The following activities are on the critical path (any delay will impact project completion):

1. **ACT-001**: Project Initiation (5 days)
2. **ACT-002**: Requirements Gathering (8 days)
3. **ACT-003**: System Design (13 days)
4. **ACT-005**: Firmware Development (31 days) - **Longest activity**
5. **ACT-010**: System Integration (20 days)
6. **ACT-012**: System Testing (15 days)
7. **ACT-015**: Deployment (10 days)

**Total Critical Path Duration**: ~102 days (4.5 months)

## Parallel Workstreams

The following activities can be executed in parallel to optimize schedule:

### Workstream 1: Hardware Track
- ACT-004: Hardware Setup
- ACT-005: Firmware Development
- ACT-006: Sensor Integration

### Workstream 2: Software Track
- ACT-007: Software Development
- ACT-008: Database Design
- ACT-009: API Development

### Workstream 3: Quality Track
- ACT-011: Unit Testing (runs parallel to integration)
- ACT-012: System Testing

### Workstream 4: Deployment Track
- ACT-013: User Training
- ACT-014: Documentation (can start before deployment)

## Milestones

| Milestone | Date | Activities Completed |
|-----------|------|---------------------|
| 🎯 M1: Requirements Complete | 2026-02-15 | ACT-001, ACT-002 |
| 🎯 M2: Design Complete | 2026-02-28 | ACT-003 |
| 🎯 M3: Development Complete | 2026-04-15 | ACT-004-009 |
| 🎯 M4: Testing Complete | 2026-05-25 | ACT-010-012 |
| 🎯 M5: Deployment Ready | 2026-06-05 | ACT-013, ACT-014 |
| 🎯 M6: Go-Live | 2026-06-15 | ACT-015 |
| 🎯 M7: Support Handoff | 2026-07-16 | ACT-016 |

## Resource Allocation by Phase

### Phase 1: Planning (Feb 3-28)
- Project Manager (Full-time)
- Business Analyst (Full-time)
- Lead Engineer (50%)

### Phase 2: Implementation (Mar 1 - Apr 15)
- Hardware Engineer (Full-time)
- Firmware Developer (Full-time)
- IoT Engineer (Full-time)
- Software Developer (Full-time)
- Database Admin (Full-time)
- Backend Developer (Full-time)

### Phase 3: Integration & Testing (Apr 16 - May 25)
- Integration Lead (Full-time)
- QA Engineer (Full-time)
- QA Lead (Full-time)

### Phase 4: Deployment (May 26 - Jun 15)
- Training Coordinator (Full-time)
- Technical Writer (Full-time)
- DevOps Engineer (Full-time)

### Phase 5: Maintenance (Jun 16 - Jul 16)
- Support Team (24/7)

## Budget Distribution

| Phase | Budget (USD) | Percentage |
|-------|-------------|------------|
| Planning | $155,000 | 16% |
| Implementation (HW) | $215,000 | 22% |
| Implementation (SW) | $250,000 | 26% |
| Integration & Testing | $160,000 | 17% |
| Deployment | $95,000 | 10% |
| Maintenance | $50,000 | 5% |
| **Total** | **$970,000** | **100%** |

## Risk Register

| Risk | Impact | Probability | Mitigation |
|------|--------|-------------|------------|
| Hardware delays | High | Medium | Order components early (ACT-004) |
| Firmware complexity | Critical | Medium | Add buffer time, senior developer |
| Integration issues | High | High | Early integration testing (ACT-010) |
| Training delays | Medium | Low | Prepare materials in advance |
| Budget overrun | High | Medium | Weekly cost tracking and reviews |

## Dependencies Map

```
ACT-001 (Project Initiation)
    └─> ACT-002 (Requirements)
            └─> ACT-003 (System Design)
                    ├─> ACT-004 (Hardware Setup)
                    │       ├─> ACT-005 (Firmware Dev)
                    │       └─> ACT-006 (Sensor Integration)
                    ├─> ACT-007 (Software Dev)
                    └─> ACT-008 (Database Design)
                            └─> ACT-009 (API Dev)

ACT-005, ACT-006, ACT-007 ──> ACT-010 (System Integration)
                                  └─> ACT-011 (Unit Testing)
                                          └─> ACT-012 (System Testing)
                                                  ├─> ACT-013 (Training)
                                                  └─> ACT-014 (Documentation)
                                                          
ACT-013, ACT-014 ──> ACT-015 (Deployment)
                        └─> ACT-016 (Support)
```

## Notes

- All dates are estimates and subject to change
- Resource availability must be confirmed before phase start
- Weekly status updates required for all activities
- Critical path activities require daily monitoring
- Budget reviews scheduled bi-weekly

---

*Generated from WBS_Activity_Management_Sheet.csv - Last Updated: 2026-02-03*

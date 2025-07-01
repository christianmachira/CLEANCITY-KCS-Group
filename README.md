# CLEAN CITY – Test Strategy

## GROUP NAME
**KCS**

## TEAM MEMBERS
1. STEPHEN MUHOHO  
2. SALMA ADAM  
3. CHRISTIAN MACHIRA  

---

## OBJECTIVES

- **Validate core business functionality**
- **Identify critical defects**
- **Assess user experience quality**
- **Validate data integrity**

---

## TOOLS

- ****

---

## SCOPE

### Functional Areas

- Home page waste pickup request form
- Dashboard request viewing and filtering
- Admin panel request management
- Feedback page functionality
- Awareness page content display
- Navigation between all pages

### Data Operations

- Form data submission and validation
- Data persistence in `localStorage`
- Request status updates
- Filtering and sorting operations
- Data display accuracy

### User Interface

- Visual layout and design consistency
- Responsive design (Desktop, Tablet, Mobile)
- Form field behavior and validation messages
- Button and link functionality
- Error message display

### User Experience

- Core user workflow completion
- Navigation usability
- Form completion experience
- Data viewing and management

### Accessibility

- Keyboard navigation
- Screen reader compatibility
- Image alt-text presence
- Form label associations
- Color contrast (basic assessment)

### Performance

- Page load times
- Basic responsiveness testing
- Large dataset handling

### Compatibility

- Primary browser testing (Chrome, Edge)
- Mobile device simulation
- Basic cross-platform validation

---

## TESTING APPROACH

### Primary Methodology: Risk-Based Testing

#### Risk Assessment Framework

**Risk Priority = Business Impact × Probability of Failure × User Impact**

#### Risk Categories

- **Critical:** Core business function failures
- **High:** Known bugs and operational impacts
- **Medium:** User experience and accessibility issues
- **Low:** Edge cases and performance optimization

#### Testing Techniques by Risk Level

**For Critical Risks:**
- Positive Testing: Verify happy path scenarios work correctly
- Negative Testing: Validate error handling and edge cases
- End-to-End Testing: Complete user workflow validation
- Data Validation: Confirm data integrity and persistence

**For High Risks:**
- Exploratory Testing: Investigate known problem areas
- Boundary Testing: Test limits and edge conditions
- Integration Testing: Verify component interactions
- Regression Testing: Ensure fixes don't break existing functionality

**For Medium Risks:**
- Usability Testing: Assess user experience across devices
- Accessibility Testing: Validate compliance with accessibility standards
- Compatibility Testing: Verify cross-browser functionality

**For Low Risks:**
- Performance Testing: Basic load time and responsiveness checks
- Stress Testing: Evaluate behavior under extreme conditions

---

### Test Design Techniques

- **Equivalence Partitioning:** Group similar input conditions
- **Boundary Value Analysis:** Test at data limits
- **Error Guessing:** Based on experience and known issues
- **Checklist-Based Testing:** Systematic coverage verification

---

### Test Execution Approach

- **Manual Testing:** Primary method for all test types
- **Structured Execution:** Follow documented test cases
- **Exploratory Sessions:** Time-boxed investigation of risk areas
- **Defect Retesting:** Verify fixes for identified issues

---

### Documentation Standards

- **Test Case Format:** Step-by-step with expected results
- **Defect Reporting:** Standardized bug report template
- **Evidence Collection:** Screenshots and detailed observations
- **Traceability:** Link tests to risks and requirements

---

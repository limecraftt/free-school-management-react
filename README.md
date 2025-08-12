├── backend
│   ├── logs
│   │   ├── access.log
│   │   ├── app.log
│   │   └── error.log
│   ├── package.json
│   ├── README.md
│   ├── render.yaml
│   ├── src
│   │   ├── app.js
│   │   ├── config
│   │   │   ├── auth.js
│   │   │   ├── cloudinary.js
│   │   │   ├── constants.js
│   │   │   ├── database.js
│   │   │   ├── email.js
│   │   │   └── environment.js
│   │   ├── controllers
│   │   │   ├── adminController.js
│   │   │   ├── authController.js
│   │   │   ├── gradeController.js
│   │   │   ├── parentController.js
│   │   │   ├── paymentController.js
│   │   │   ├── pdfController.js
│   │   │   ├── reportController.js
│   │   │   ├── settingsController.js
│   │   │   ├── studentController.js
│   │   │   ├── teacherController.js
│   │   │   └── uploadController.js
│   │   ├── middleware
│   │   │   ├── auth.js
│   │   │   ├── cors.js
│   │   │   ├── errorHandler.js
│   │   │   ├── logger.js
│   │   │   ├── rateLimiter.js
│   │   │   ├── roleAuth.js
│   │   │   ├── sanitizer.js
│   │   │   ├── upload.js
│   │   │   └── validation.js
│   │   ├── models
│   │   │   ├── AcademicYear.js
│   │   │   ├── ActivityLog.js
│   │   │   ├── Class.js
│   │   │   ├── Grade.js
│   │   │   ├── index.js
│   │   │   ├── Payment.js
│   │   │   ├── School.js
│   │   │   ├── Student.js
│   │   │   └── User.js
│   │   ├── routes
│   │   │   ├── admin.js
│   │   │   ├── auth.js
│   │   │   ├── grades.js
│   │   │   ├── index.js
│   │   │   ├── parent.js
│   │   │   ├── payments.js
│   │   │   ├── pdf.js
│   │   │   ├── reports.js
│   │   │   ├── settings.js
│   │   │   ├── students.js
│   │   │   ├── teacher.js
│   │   │   └── uploads.js
│   │   ├── server.js
│   │   ├── services
│   │   │   ├── activityService.js
│   │   │   ├── analyticsService.js
│   │   │   ├── authService.js
│   │   │   ├── backupService.js
│   │   │   ├── emailService.js
│   │   │   ├── gradeService.js
│   │   │   ├── paymentService.js
│   │   │   ├── pdfService.js
│   │   │   ├── reportService.js
│   │   │   └── studentService.js
│   │   ├── templates
│   │   │   ├── email
│   │   │   │   ├── grade-report.html
│   │   │   │   ├── payment-receipt.html
│   │   │   │   ├── payment-reminder.html
│   │   │   │   └── welcome.html
│   │   │   └── pdf
│   │   │       ├── class-report.js
│   │   │       ├── grade-report.js
│   │   │       ├── payment-receipt.js
│   │   │       └── student-certificate.js
│   │   └── utils
│   │       ├── constants.js
│   │       ├── database.js
│   │       ├── dateUtils.js
│   │       ├── encryption.js
│   │       ├── fileUtils.js
│   │       ├── formatters.js
│   │       ├── gradeCalculators.js
│   │       ├── helpers.js
│   │       ├── seeders.js
│   │       └── validators.js
│   ├── tests
│   │   ├── integration
│   │   │   ├── admin.test.js
│   │   │   ├── auth.test.js
│   │   │   ├── parent.test.js
│   │   │   └── teacher.test.js
│   │   ├── setup.js
│   │   └── unit
│   │       ├── controllers
│   │       ├── models
│   │       └── services
│   └── uploads
│       └── temp
├── deploy.md
├── frontend
│   ├── package.json
│   ├── postcss.config.js
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── manifest.json
│   │   └── robots.txt
│   ├── README.md
│   ├── src
│   │   ├── App.jsx
│   │   ├── assets
│   │   │   ├── icons
│   │   │   │   ├── dashboard.svg
│   │   │   │   ├── grades.svg
│   │   │   │   ├── lunch.svg
│   │   │   │   ├── payments.svg
│   │   │   │   ├── pdf.svg
│   │   │   │   ├── reports.svg
│   │   │   │   └── students.svg
│   │   │   └── images
│   │   │       ├── admin-avatar.png
│   │   │       ├── logo.png
│   │   │       ├── parent-avatar.png
│   │   │       ├── school-banner.jpg
│   │   │       ├── student-placeholder.png
│   │   │       └── teacher-avatar.png
│   │   ├── components
│   │   │   ├── charts
│   │   │   │   ├── BarChart.jsx
│   │   │   │   ├── LineChart.jsx
│   │   │   │   ├── PaymentTrendsChart.jsx
│   │   │   │   ├── PerformanceChart.jsx
│   │   │   │   ├── PieChart.jsx
│   │   │   │   └── StatsCard.jsx
│   │   │   ├── common
│   │   │   │   ├── ConfirmDialog.jsx
│   │   │   │   ├── DataTable.jsx
│   │   │   │   ├── ErrorBoundary.jsx
│   │   │   │   ├── Footer.jsx
│   │   │   │   ├── Header.jsx
│   │   │   │   ├── LoadingSpinner.jsx
│   │   │   │   ├── Modal.jsx
│   │   │   │   ├── Pagination.jsx
│   │   │   │   ├── PDFDownloadButton.jsx
│   │   │   │   ├── SearchBar.jsx
│   │   │   │   ├── Sidebar.jsx
│   │   │   │   └── StatusBadge.jsx
│   │   │   ├── filters
│   │   │   │   ├── ClassFilter.jsx
│   │   │   │   ├── DateRangeFilter.jsx
│   │   │   │   ├── PaymentFilter.jsx
│   │   │   │   └── StudentFilter.jsx
│   │   │   ├── forms
│   │   │   │   ├── FormField.jsx
│   │   │   │   ├── GradeEntryForm.jsx
│   │   │   │   ├── PaymentForm.jsx
│   │   │   │   ├── PaymentStatusForm.jsx
│   │   │   │   ├── SchoolSettingsForm.jsx
│   │   │   │   └── StudentForm.jsx
│   │   │   ├── layout
│   │   │   │   ├── AdminLayout.jsx
│   │   │   │   ├── AuthLayout.jsx
│   │   │   │   ├── DashboardLayout.jsx
│   │   │   │   ├── ParentLayout.jsx
│   │   │   │   ├── PublicLayout.jsx
│   │   │   │   └── TeacherLayout.jsx
│   │   │   └── ui
│   │   │       ├── Alert.jsx
│   │   │       ├── Badge.jsx
│   │   │       ├── Button.jsx
│   │   │       ├── Card.jsx
│   │   │       ├── Dropdown.jsx
│   │   │       ├── Input.jsx
│   │   │       ├── Select.jsx
│   │   │       └── Tabs.jsx
│   │   ├── config.js
│   │   ├── context
│   │   │   ├── AuthContext.jsx
│   │   │   ├── NotificationContext.jsx
│   │   │   ├── SchoolContext.jsx
│   │   │   ├── StudentContext.jsx
│   │   │   └── ThemeContext.jsx
│   │   ├── hooks
│   │   │   ├── useApi.js
│   │   │   ├── useAuth.js
│   │   │   ├── useDebounce.js
│   │   │   ├── useFilters.js
│   │   │   ├── useLocalStorage.js
│   │   │   ├── useModal.js
│   │   │   ├── useNotification.js
│   │   │   ├── usePagination.js
│   │   │   ├── usePDF.js
│   │   │   ├── useSearch.js
│   │   │   ├── useStudentData.js
│   │   │   └── useTable.js
│   │   ├── index.js
│   │   ├── pages
│   │   │   ├── admin
│   │   │   │   ├── AcademicReports.jsx
│   │   │   │   ├── AcademicYear.jsx
│   │   │   │   ├── AdminDashboard.jsx
│   │   │   │   ├── AdminReports.jsx
│   │   │   │   ├── FeeStructure.jsx
│   │   │   │   ├── FinancialOverview.jsx
│   │   │   │   ├── FinancialReports.jsx
│   │   │   │   ├── LunchFeeTracking.jsx
│   │   │   │   ├── ParentManagement.jsx
│   │   │   │   ├── PerformanceAnalytics.jsx
│   │   │   │   ├── SchoolFeeTracking.jsx
│   │   │   │   ├── SchoolOverview.jsx
│   │   │   │   ├── SchoolSettings.jsx
│   │   │   │   ├── StudentActivity.jsx
│   │   │   │   ├── StudentManagement.jsx
│   │   │   │   ├── SystemBackup.jsx
│   │   │   │   └── TeacherManagement.jsx
│   │   │   ├── auth
│   │   │   │   ├── ForgotPassword.jsx
│   │   │   │   ├── Login.jsx
│   │   │   │   ├── Register.jsx
│   │   │   │   ├── ResetPassword.jsx
│   │   │   │   └── RoleSelector.jsx
│   │   │   ├── parent
│   │   │   │   ├── ChildProfile.jsx
│   │   │   │   ├── FeeStructureView.jsx
│   │   │   │   ├── GradeHistory.jsx
│   │   │   │   ├── GradeViewer.jsx
│   │   │   │   ├── ParentDashboard.jsx
│   │   │   │   ├── PaymentHistory.jsx
│   │   │   │   ├── PaymentStatus.jsx
│   │   │   │   ├── PDFReports.jsx
│   │   │   │   ├── ProgressReports.jsx
│   │   │   │   ├── SchoolAnnouncements.jsx
│   │   │   │   ├── StudentSearch.jsx
│   │   │   │   ├── StudentSelector.jsx
│   │   │   │   └── TeacherMessages.jsx
│   │   │   ├── shared
│   │   │   │   ├── FAQ.jsx
│   │   │   │   ├── Help.jsx
│   │   │   │   ├── Profile.jsx
│   │   │   │   ├── Settings.jsx
│   │   │   │   └── Support.jsx
│   │   │   └── teacher
│   │   │       ├── ClassAttendance.jsx
│   │   │       ├── ClassOverview.jsx
│   │   │       ├── ClassReports.jsx
│   │   │       ├── GradeEntry.jsx
│   │   │       ├── GradeManagement.jsx
│   │   │       ├── LunchFeeStatus.jsx
│   │   │       ├── ParentCommunication.jsx
│   │   │       ├── PaymentFilters.jsx
│   │   │       ├── PaymentStatusUpdate.jsx
│   │   │       ├── SchoolFeeStatus.jsx
│   │   │       ├── StudentFilters.jsx
│   │   │       ├── StudentGrades.jsx
│   │   │       ├── StudentProgress.jsx
│   │   │       └── TeacherDashboard.jsx
│   │   ├── routes.js
│   │   ├── services
│   │   │   ├── api.js
│   │   │   ├── authService.js
│   │   │   ├── emailService.js
│   │   │   ├── gradeService.js
│   │   │   ├── paymentService.js
│   │   │   ├── pdfService.js
│   │   │   ├── reportService.js
│   │   │   ├── settingsService.js
│   │   │   ├── studentService.js
│   │   │   └── uploadService.js
│   │   └── utils
│   │       ├── chartHelpers.js
│   │       ├── constants.js
│   │       ├── dateUtils.js
│   │       ├── filterUtils.js
│   │       ├── formatters.js
│   │       ├── gradeCalculators.js
│   │       ├── helpers.js
│   │       ├── pdfGenerators.js
│   │       ├── tailwindHelpers.js
│   │       └── validators.js
│   ├── tailwind.config.js
│   └── vercel.json
├── LICENSE
├── package.json
├── README.md
└── shared
    ├── constants
    │   ├── apiEndpoints.js
    │   ├── gradeSystem.js
    │   ├── paymentTypes.js
    │   └── userRoles.js
    ├── package.json
    └── utils
        ├── dateFormats.js
        ├── formatters.js
        └── validationRules.js


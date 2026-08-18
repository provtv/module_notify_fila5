# Graph Report - /var/www/_bases/base_ptvx_fila5/laravel/Modules/Notify  (2026-08-04)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 2102 nodes · 3377 edges · 396 communities (349 shown, 47 thin omitted)
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 58 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `7392c5be`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Illuminate\Database\Eloquent\Model
- Illuminate\Database\Seeder
- WhatsAppData
- HasTenantNotifications.php
- TestCase
- PushNotificationData
- Spatie\QueueableAction\QueueableAction
- rules
- NotificationTemplate
- devDependencies
- NotifyBasePolicy
- TelegramData
- SmtpData
- NotificationLog.php
- NotificationsCoverageTest.php
- Modules\Xot\Filament\Pages\XotBasePage
- MailTemplate.php
- Illuminate\Support\Collection
- Illuminate\Bus\Queueable
- SendRecordsNotificationAction.php
- NotifyModelsCoverageTest.php
- PushNotificationService
- app.json
- Modules\Xot\Filament\Resources\Tables\XotBaseResourceTable
- NotifyFilamentResourcesCoverageTest.php
- NotifyThemeAndColumnsCoverageTest.php
- NotifyTheme
- Illuminate\Database\Eloquent\Factories\Factory
- contributor-lines-report.mjs
- Illuminate\Notifications\Notification
- MailTemplateResource.php
- Modules\Xot\Filament\Resources\Schemas\XotBaseResourceInfolist
- update-roadmaps.sh
- SmsData
- SpatieEmail
- NotificationManagerTest
- Modules\Notify\Contracts\SMS\SmsActionContract
- EmailDataEmail
- Modules\Xot\Filament\Resources\Schemas\XotBaseResourceForm
- BaseModel
- Notification
- Pest.php
- NotificationManagementBusinessLogicTest.php
- ThemeNotification
- install-quality-tools.sh
- SmsData.php
- SendNotificationAction
- NotificationData
- SendPushNotification
- require
- TwilioData
- Spatie\LaravelData\Data
- EmailData
- NotifyDatasCoverageTest.php
- NotificationResource.php
- Modules\Xot\Filament\Resources\Pages\XotBaseEditRecord
- Modules\Xot\Filament\Resources\Pages\XotBaseListRecords
- composer.json
- keywords
- config.php
- SendAwsEmailPage
- AgiletelecomData
- FirebaseAndroidNotification
- SendEmailPage
- SendNetfunSmsPage
- SendSmsPage
- SendSpatieEmailPage
- SendWhatsAppPage
- ConfigHelper
- PlivoData
- SendSmsFactorSMSAction
- SendEmail
- SendFirebasePushNotificationPage
- Filament\Panel
- SendTelegram
- SendTelegramPage
- Modules\Xot\Filament\Resources\Pages\XotBaseCreateRecord
- scripts
- Carbon\Carbon
- GammuData
- NexmoData
- SmsFactorData
- SendPushNotificationPage
- TestSmtpPage
- ContactSection
- RecordNotification
- NotifyServiceProvider.php
- MailtrapEngine
- SmsService
- HasNotificationTracking.php
- MediaTypeEnum.php
- TelegramDriverEnum.php
- WhatsAppDriverEnum.php
- NotificationChannelFactory
- NetfunChannelNotifiableDummy
- AttachmentData
- SmsNotification
- allow-plugins
- laravel
- HasContactDummyModel
- screenshot-group-b.js
- EsendexSendAction.php
- SendNotificationToRecipientAction.php
- FirebaseNotificationData
- NetfunSmsResponseData
- SettingPage
- EventServiceProvider
- psr-4
- samples/widgets.blade.php
- widgets/mail.blade.php
- emails/welcome.blade.php
- ListMailTemplates.php
- LinkableRelationManager.php
- samples/minty.blade.php
- samples/sunny.blade.php
- minty/mail.blade.php
- sunny/mail.blade.php
- samples/ark.blade.php
- ark/mail.blade.php
- Test
- Dashboard.php
- RouteServiceProvider.php
- benchmark.sh
- webpack.mix.js
- notify::emails.templates.
- send-telegram.blade.php
- send-whatsapp.blade.php
- code-quality-check.sh
- code-quality-fix.sh
- fix-code-quality-issues.sh
- full-code-quality-check.sh
- test-homepage.js
- test-homepage2.js
- GenericNotification

## God Nodes (most connected - your core abstractions)
1. `TestCase` - 101 edges
2. `NotificationTemplate` - 50 edges
3. `SmsData` - 44 edges
4. `Notification` - 43 edges
5. `rules` - 27 edges
6. `PushNotificationService` - 25 edges
7. `PushNotificationData` - 24 edges
8. `MailTemplate` - 20 edges
9. `WhatsAppData` - 19 edges
10. `SpatieEmail` - 18 edges

## Surprising Connections (you probably didn't know these)
- `execute()` --references--> `SmsData`  [EXTRACTED]
  tests/Unit/Notifications/Channels/NotificationsChannelsTest.php → app/Datas/SmsData.php
- `TestCase` --references--> `NotificationManager`  [EXTRACTED]
  tests/TestCase.php → app/Actions/NotificationManager.php
- `ViewNotificationTestProxy` --inherits--> `ViewNotification`  [EXTRACTED]
  tests/Fixtures/ViewNotificationTestProxy.php → app/Filament/Resources/NotificationResource/Pages/ViewNotification.php
- `makePreviewNotificationTemplateTestProxy()` --references--> `PreviewNotificationTemplate`  [EXTRACTED]
  tests/Unit/Filament/Resources/NotifyFilamentResourcesCoverageTest.php → app/Filament/Resources/NotificationTemplateResource/Pages/PreviewNotificationTemplate.php
- `NotifyNotificationTemplateProxy` --inherits--> `NotificationTemplate`  [EXTRACTED]
  tests/Fixtures/NotifyNotificationTemplateProxy.php → app/Models/NotificationTemplate.php

## Import Cycles
- None detected.

## Communities (396 total, 47 thin omitted)

### Community 0 - "Illuminate\Database\Eloquent\Model"
Cohesion: 0.07
Nodes (19): SendRecordNotificationAction, getRecipient(), getRecordEmail(), getRecordPhone(), getRecordWhatsApp(), EmailTemplate, Theme, Illuminate\Database\Eloquent\Model (+11 more)

### Community 1 - "Illuminate\Database\Seeder"
Cohesion: 0.06
Nodes (16): ContactSeeder, DatabaseSeeder, MailTemplateLogSeeder, MailTemplateSeeder, MailTemplatesSeeder, MailTemplateVersionSeeder, NotificationChannelSeeder, NotificationLogSeeder (+8 more)

### Community 2 - "WhatsAppData"
Cohesion: 0.07
Nodes (12): Send360dialogWhatsAppAction, SendFacebookWhatsAppAction, SendTwilioWhatsAppAction, SendVonageWhatsAppAction, WhatsAppChannel, execute(), execute(), WhatsAppData (+4 more)

### Community 3 - "HasTenantNotifications.php"
Cohesion: 0.07
Nodes (19): belongsToCurrentTenant(), belongsToTenant(), bootHasTenantNotifications(), getTenantId(), notifications(), readNotifications(), scopeForTenant(), tenantNotificationLogs() (+11 more)

### Community 4 - "TestCase"
Cohesion: 0.07
Nodes (8): Get, NotifyThemeData, getDefault(), self, Illuminate\Foundation\Application, Illuminate\Foundation\Testing\DatabaseTransactions, Modules\Xot\Tests\XotBaseTestCase, TestCase

### Community 5 - "PushNotificationData"
Cohesion: 0.08
Nodes (9): SendPushToAllUsersAction, SendPushToDeviceAction, SendPushToDevicesAction, SendPushToPlatformAction, SendPushToTopicAction, SendPushWithTargetingAction, SendPushWithTemplateAction, PushCriteriaData (+1 more)

### Community 6 - "Spatie\QueueableAction\QueueableAction"
Cohesion: 0.07
Nodes (12): SendDuocircleMailAction, TryDuocircleMailAction, GetMailLayoutAction, SendMailAction, SendMailtrapMailAction, TryMailAction, NormalizePhoneNumberAction, SendAppointmentNotificationAction (+4 more)

### Community 7 - "rules"
Cohesion: 0.05
Nodes (37): bootstrap/cache/**/*, *.min.css, node_modules/**/*, public/build/**/*, storage/**/*, stylelint-config-prettier, stylelint-config-standard, vendor/**/* (+29 more)

### Community 8 - "NotificationTemplate"
Cohesion: 0.09
Nodes (6): NotificationManager, NotificationTemplate, self, NotificationManager, Illuminate\Database\Eloquent\Collection, assertFirstModel()

### Community 9 - "devDependencies"
Cohesion: 0.06
Nodes (34): autoprefixer, axios, dotenv, dotenv-expand, laravel-mix, laravel-mix-merge-manifest, lodash, devDependencies (+26 more)

### Community 10 - "NotifyBasePolicy"
Cohesion: 0.07
Nodes (14): RecordNotificationData, ContactPolicy, MailTemplateLogPolicy, MailTemplatePolicy, MailTemplateVersionPolicy, NotificationPolicy, NotificationTemplatePolicy, NotificationTemplateVersionPolicy (+6 more)

### Community 11 - "TelegramData"
Cohesion: 0.11
Nodes (10): SendBotmanTelegramAction, SendNutgramTelegramAction, SendOfficialTelegramAction, TelegramChannel, execute(), execute(), TelegramData, TelegramProviderActionInterface (+2 more)

### Community 12 - "SmtpData"
Cohesion: 0.10
Nodes (9): AnalyzeTranslationFiles, SendMailCommand, TelegramWebhook, self, SmtpData, Command, Illuminate\Console\Command, Symfony\Component\Mailer\Mailer (+1 more)

### Community 13 - "NotificationLog.php"
Cohesion: 0.09
Nodes (8): MailTemplateLog, MailTemplateVersion, NotificationLog, self, Illuminate\Database\Eloquent\Builder, Illuminate\Database\Eloquent\Relations\BelongsTo, Illuminate\Database\Eloquent\Relations\MorphTo, Illuminate\Database\Eloquent\SoftDeletes

### Community 14 - "NotificationsCoverageTest.php"
Cohesion: 0.13
Nodes (6): BuildMailMessageAction, TicketAssignedNotification, TicketStatusChangedNotification, Illuminate\Notifications\Messages\MailMessage, Modules\User\Models\User, makeThemeNotifiableDummy()

### Community 15 - "Modules\Xot\Filament\Pages\XotBasePage"
Cohesion: 0.22
Nodes (11): BackedEnum, SlackNotification, BackedEnum, SlackNotificationPage, Filament\Forms\Components\Select, Filament\Notifications\Notification, Filament\Schemas\Schema, Illuminate\Contracts\Auth\Authenticatable (+3 more)

### Community 16 - "MailTemplate.php"
Cohesion: 0.11
Nodes (12): MailTemplate, MailTemplateFactory, Illuminate\Contracts\Mail\Mailable, SlugOptions, Spatie\MailTemplates\Models\MailTemplate, Spatie\Sluggable\HasSlug, Spatie\Sluggable\SlugOptions, Spatie\Translatable\HasTranslations (+4 more)

### Community 17 - "Illuminate\Support\Collection"
Cohesion: 0.16
Nodes (12): getMobileDeviceTokens(), self, PushNotificationDebugData, SendNotificationBulkResultData, FirebaseCloudMessagingChannel, Illuminate\Contracts\Support\Arrayable, Illuminate\Support\Collection, Kreait\Firebase\Contract\Messaging (+4 more)

### Community 18 - "Illuminate\Bus\Queueable"
Cohesion: 0.17
Nodes (11): SchedulePushNotificationAction, SendNotificationJob, SendScheduledPushNotification, AppointmentNotificationMail, DateTime, Illuminate\Bus\Queueable, Illuminate\Contracts\Queue\ShouldQueue, Illuminate\Foundation\Bus\Dispatchable (+3 more)

### Community 19 - "SendRecordsNotificationAction.php"
Cohesion: 0.11
Nodes (10): SendRecordsNotificationAction, SendRecordsNotificationBulkAction, ChannelCheckboxList, static, MailTemplateSelect, static, Filament\Forms\Components\CheckboxList, Modules\Xot\Filament\Tables\Actions\XotBaseBulkAction (+2 more)

### Community 20 - "NotifyModelsCoverageTest.php"
Cohesion: 0.13
Nodes (11): BaseMorphPivot, BasePivot, Illuminate\Database\Eloquent\Relations\MorphPivot, Illuminate\Database\Eloquent\Relations\Pivot, Modules\Xot\Traits\Updater, NotifyBaseMorphPivotProxy, NotifyBasePivotProxy, NotifyNotificationTemplateProxy (+3 more)

### Community 22 - "app.json"
Cohesion: 0.09
Nodes (22): alwaysUpdateLinks, attachmentFolderPath, autoConvertHtml, defaultEditMode, defaultViewMode, foldHeading, foldIndent, legacyEditor (+14 more)

### Community 23 - "Modules\Xot\Filament\Resources\Tables\XotBaseResourceTable"
Cohesion: 0.12
Nodes (7): ContactsTable, MailTemplatesTable, NotificationLogsTable, NotificationsTable, NotificationTemplatesTable, NotifyThemesTable, Modules\Xot\Filament\Resources\Tables\XotBaseResourceTable

### Community 24 - "NotifyFilamentResourcesCoverageTest.php"
Cohesion: 0.14
Nodes (9): PreviewMailTemplate, NotificationTemplateResource, PreviewNotificationTemplate, Modules\Xot\Filament\Resources\Pages\XotBaseResourcePage, PreviewMailTemplateTestProxy, ViewNotificationTestProxy, makePreviewMailTemplateTestProxy(), makePreviewNotificationTemplateTestProxy() (+1 more)

### Community 25 - "NotifyThemeAndColumnsCoverageTest.php"
Cohesion: 0.13
Nodes (7): NotifyThemeResource, EditNotifyTheme, ListNotifyThemes, ContactColumn, Filament\Tables\Columns\ViewColumn, EditNotifyThemeTestProxy, makeEditNotifyThemeTestProxy()

### Community 26 - "NotifyTheme"
Cohesion: 0.12
Nodes (6): NotifyTheme, NotifyThemeable, NotifyThemeableFactory, static, NotifyThemeFactory, notifyThemeForThemeable()

### Community 27 - "Illuminate\Database\Eloquent\Factories\Factory"
Cohesion: 0.14
Nodes (7): NotificationChannel, ContactFactory, MailTemplateLogFactory, MailTemplateVersionFactory, NotificationLogFactory, NotificationTemplateFactory, Illuminate\Database\Eloquent\Factories\Factory

### Community 28 - "contributor-lines-report.mjs"
Cohesion: 0.16
Nodes (19): args, barChartSvg(), buildHtml(), buildSummary(), clocData, collectCloc(), collectGitChurn(), cwd (+11 more)

### Community 29 - "Illuminate\Notifications\Notification"
Cohesion: 0.15
Nodes (7): broadcast(), dispatch(), broadcast(), dispatch(), TelegramChannel, TelegramNotification, Illuminate\Notifications\Notification

### Community 30 - "MailTemplateResource.php"
Cohesion: 0.13
Nodes (9): HtmlLayoutPathSelect, static, MailTemplateResource, CreateMailTemplate, EditMailTemplate, MailTemplateForm, Modules\Lang\Filament\Resources\LangBaseResource, Modules\Lang\Filament\Resources\Pages\LangBaseCreateRecord (+1 more)

### Community 31 - "Modules\Xot\Filament\Resources\Schemas\XotBaseResourceInfolist"
Cohesion: 0.14
Nodes (7): ContactInfolist, MailTemplateInfolist, NotificationLogInfolist, NotificationInfolist, NotificationTemplateInfolist, NotifyThemeInfolist, Modules\Xot\Filament\Resources\Schemas\XotBaseResourceInfolist

### Community 32 - "update-roadmaps.sh"
Cohesion: 0.33
Nodes (17): create_module_roadmap(), create_theme_roadmap(), generate_consolidated_report(), log(), main(), notify_stakeholders(), update-roadmaps.sh script, success() (+9 more)

### Community 33 - "SmsData"
Cohesion: 0.13
Nodes (8): NetfunSendAction, SendAgiletelecomSMSAction, SendNetfunSMSAction, execute(), execute(), execute(), self, SmsData

### Community 34 - "SpatieEmail"
Cohesion: 0.18
Nodes (6): self, SpatieEmail, Attachment, Illuminate\Mail\Mailables\Attachment, Spatie\MailTemplates\Interfaces\MailTemplateInterface, Spatie\MailTemplates\TemplateMailable

### Community 35 - "NotificationManagerTest"
Cohesion: 0.22
Nodes (6): Mockery\CompositeExpectation, Mockery\MockInterface, PHPUnit\Framework\TestCase, mockExpectation(), typedMock(), NotificationManagerTest

### Community 36 - "Modules\Notify\Contracts\SMS\SmsActionContract"
Cohesion: 0.21
Nodes (4): SendGammuSMSAction, SendNexmoSMSAction, SmsActionFactory, Modules\Notify\Contracts\SMS\SmsActionContract

### Community 37 - "EmailDataEmail"
Cohesion: 0.15
Nodes (5): EmailDataEmail, ChristmasGreetingMailable, Illuminate\Mail\Mailable, Illuminate\Mail\Mailables\Content, Illuminate\Mail\Mailables\Envelope

### Community 38 - "Modules\Xot\Filament\Resources\Schemas\XotBaseResourceForm"
Cohesion: 0.15
Nodes (6): ContactForm, NotificationLogForm, NotificationForm, NotificationTemplateForm, NotifyThemeForm, Modules\Xot\Filament\Resources\Schemas\XotBaseResourceForm

### Community 39 - "BaseModel"
Cohesion: 0.15
Nodes (6): BaseModel, NotificationTemplateVersion, NotificationTemplateVersionFactory, Modules\Xot\Models\XotBaseModel, Spatie\MediaLibrary\HasMedia, Spatie\MediaLibrary\InteractsWithMedia

### Community 40 - "Notification"
Cohesion: 0.19
Nodes (5): Notification, NotificationFactory, Modules\Xot\Models\BaseModel, createNotification(), makeNotification()

### Community 41 - "Pest.php"
Cohesion: 0.17
Nodes (9): ReflectionType, assertFreshModel(), assertReflectionFilename(), assertReflectionNamedType(), assertReflectionTypeName(), notifyFreshTypeChannels(), notifyFreshTypeSettings(), notifyReflectionPropertyNames() (+1 more)

### Community 42 - "NotificationManagementBusinessLogicTest.php"
Cohesion: 0.17
Nodes (5): Contact, NotificationType, NotificationTypeFactory, Illuminate\Database\Eloquent\Factories\HasFactory, Illuminate\Support\Carbon

### Community 43 - "ThemeNotification"
Cohesion: 0.21
Nodes (6): NetfunChannel, ThemeNotification, Modules\Notify\Contracts\CanThemeNotificationContract, execute(), makeTelegramNotificationDummy(), makeThemeNotificationDummy()

### Community 44 - "install-quality-tools.sh"
Cohesion: 0.43
Nodes (14): check_prerequisites(), create_configurations(), create_pre_commit_hook(), create_quality_scripts(), error(), install_frontend_tools(), install_infrastructure_tools(), install_php_tools() (+6 more)

### Community 46 - "SendNotificationAction"
Cohesion: 0.22
Nodes (3): SendNotificationAction, actionsNotificationManagerRecipient(), makeDummySendNotificationRecipient()

### Community 47 - "NotificationData"
Cohesion: 0.18
Nodes (5): getModel(), getNotificationData(), NotificationData, NotificationModel, Spatie\LaravelData\DataCollection

### Community 48 - "SendPushNotification"
Cohesion: 0.17
Nodes (4): BackedEnum, SendPushNotification, CloudMessage, Kreait\Firebase\Messaging\CloudMessage

### Community 49 - "require"
Cohesion: 0.15
Nodes (13): require, aws/aws-sdk-php, filament/filament, illuminate/contracts, illuminate/support, irazasyed/telegram-bot-sdk, kreait/laravel-firebase, laravel-notification-channels/fcm (+5 more)

### Community 50 - "TwilioData"
Cohesion: 0.21
Nodes (3): SendTwilioSMSAction, self, TwilioData

### Community 51 - "Spatie\LaravelData\Data"
Cohesion: 0.23
Nodes (4): BeautyEmailData, EmailAttachmentData, NetfunSmsData, Spatie\LaravelData\Data

### Community 52 - "EmailData"
Cohesion: 0.21
Nodes (4): EmailData, EmailDataNotification, Symfony\Component\Mime\Address, Symfony\Component\Mime\Email

### Community 53 - "NotifyDatasCoverageTest.php"
Cohesion: 0.17
Nodes (4): NetfunSmsMessage, NetfunSmsRequestData, self, SmsMessageData

### Community 54 - "NotificationResource.php"
Cohesion: 0.21
Nodes (5): ContactResource, NotificationResource, ViewNotification, Modules\Xot\Filament\Resources\Pages\XotBaseViewRecord, Modules\Xot\Filament\Resources\XotBaseResource

### Community 55 - "Modules\Xot\Filament\Resources\Pages\XotBaseEditRecord"
Cohesion: 0.23
Nodes (6): EditContact, EditNotification, EditNotificationTemplate, Modules\Xot\Filament\Resources\Pages\XotBaseEditRecord, EditContactTestProxy, makeEditContactTestProxy()

### Community 56 - "Modules\Xot\Filament\Resources\Pages\XotBaseListRecords"
Cohesion: 0.21
Nodes (4): ListContacts, ListNotifications, ListNotificationTemplates, Modules\Xot\Filament\Resources\Pages\XotBaseListRecords

### Community 57 - "composer.json"
Cohesion: 0.17
Nodes (11): authors, autoload-dev, psr-4, description, homepage, license, minimum-stability, name (+3 more)

### Community 58 - "keywords"
Cohesion: 0.17
Nodes (12): keywords, email, fcm, filament, laravel, laraxot, module_notify, notifications (+4 more)

### Community 59 - "config.php"
Cohesion: 0.24
Nodes (4): mergeChannelConfig(), mergeNotifyCompanyConfig(), mergeNotifyMailLayoutConfig(), mergeNotifyModuleConfigFromEnv()

### Community 61 - "AgiletelecomData"
Cohesion: 0.24
Nodes (4): SendAgiletelecomSMSv1Action, SendAgiletelecomSMSv2Action, AgiletelecomData, self

### Community 62 - "FirebaseAndroidNotification"
Cohesion: 0.24
Nodes (3): toCloudMessage(), FirebaseAndroidNotification, Kreait\Firebase\Messaging\Message

### Community 69 - "PlivoData"
Cohesion: 0.24
Nodes (3): SendPlivoSMSAction, self, PlivoData

### Community 70 - "SendSmsFactorSMSAction"
Cohesion: 0.31
Nodes (3): SendSmsFactorSMSAction, NetfunChannel, SmsChannel

### Community 73 - "Filament\Panel"
Cohesion: 0.28
Nodes (3): AdminPanelProvider, Filament\Panel, Modules\Xot\Providers\Filament\XotBasePanelProvider

### Community 76 - "Modules\Xot\Filament\Resources\Pages\XotBaseCreateRecord"
Cohesion: 0.33
Nodes (5): CreateContact, CreateNotification, CreateNotificationTemplate, CreateNotifyTheme, Modules\Xot\Filament\Resources\Pages\XotBaseCreateRecord

### Community 77 - "scripts"
Cohesion: 0.22
Nodes (9): scripts, analyse, format, post-autoload-dump1, post-update-cmd, test, test-coverage, Illuminate\\Foundation\\ComposerScripts::postUpdate (+1 more)

### Community 78 - "Carbon\Carbon"
Cohesion: 0.39
Nodes (3): DetermineSeasonalContentViewPathAction, Carbon, Carbon\Carbon

### Community 84 - "ContactSection"
Cohesion: 0.36
Nodes (3): ContactSection, Modules\Xot\Filament\Schemas\Components\XotBaseSection, ContactSectionTestProxy

### Community 86 - "NotifyServiceProvider.php"
Cohesion: 0.32
Nodes (3): NotifyServiceProvider, Modules\Notify\Providers\Concerns\MergesNotifyConfigFromEnv, Modules\Xot\Providers\XotBaseServiceProvider

### Community 89 - "HasNotificationTracking.php"
Cohesion: 0.39
Nodes (6): addLinkTracking(), addTracking(), addTrackingPixel(), isLinkTrackingEnabled(), isPixelTrackingEnabled(), isTrackingEnabled()

### Community 90 - "MediaTypeEnum.php"
Cohesion: 0.33
Nodes (3): getDefault(), isSupported(), self

### Community 91 - "TelegramDriverEnum.php"
Cohesion: 0.33
Nodes (3): getDefault(), isSupported(), self

### Community 92 - "WhatsAppDriverEnum.php"
Cohesion: 0.33
Nodes (3): getDefault(), isSupported(), self

### Community 98 - "allow-plugins"
Cohesion: 0.33
Nodes (6): dealerdirect/phpcodesniffer-composer-installer, pestphp/pest-plugin, wikimedia/composer-merge-plugin, config, allow-plugins, sort-packages

### Community 99 - "laravel"
Cohesion: 0.33
Nodes (6): extra, laravel, aliases, providers, Modules\\Notify\\Providers\\Filament\\AdminPanelProvider, Modules\\Notify\\Providers\\NotifyServiceProvider

### Community 100 - "HasContactDummyModel"
Cohesion: 0.47
Nodes (3): Modules\Notify\Models\Traits\HasContact, HasContactDummyModel, makeHasContactDummyModel()

### Community 101 - "screenshot-group-b.js"
Cohesion: 0.33
Nodes (4): { chromium }, fs, PAGES, path

### Community 109 - "psr-4"
Cohesion: 0.40
Nodes (5): autoload, psr-4, Modules\\Notify\\, Modules\\Notify\\Database\\Factories\\, Modules\\Notify\\Database\\Seeders\\

### Community 110 - "samples/widgets.blade.php"
Cohesion: 0.40
Nodes (4): notify::emails.templates.widgets.articleEnd, notify::emails.templates.widgets.articleStart, notify::emails.templates.widgets.newfeatureEnd, notify::emails.templates.widgets.newfeatureStart

### Community 111 - "widgets/mail.blade.php"
Cohesion: 0.40
Nodes (4): notify::emails.templates.widgets.articleEnd, notify::emails.templates.widgets.articleStart, notify::emails.templates.widgets.newfeatureEnd, notify::emails.templates.widgets.newfeatureStart

### Community 112 - "emails/welcome.blade.php"
Cohesion: 0.40
Nodes (4): notify::emails.templates.widgets.articleEnd, notify::emails.templates.widgets.articleStart, notify::emails.templates.widgets.newfeatureEnd, notify::emails.templates.widgets.newfeatureStart

### Community 115 - "samples/minty.blade.php"
Cohesion: 0.50
Nodes (3): beautymail::templates.minty.contentEnd, beautymail::templates.minty.contentStart, beautymail::templates.minty.button

### Community 116 - "samples/sunny.blade.php"
Cohesion: 0.50
Nodes (3): beautymail::templates.sunny.contentEnd, beautymail::templates.sunny.contentStart, beautymail::templates.sunny.button

### Community 117 - "minty/mail.blade.php"
Cohesion: 0.50
Nodes (3): notify::emails.templates.minty.contentEnd, notify::emails.templates.minty.contentStart, beautymail::templates.minty.button

### Community 118 - "sunny/mail.blade.php"
Cohesion: 0.50
Nodes (3): notify::emails.templates.sunny.contentEnd, notify::emails.templates.sunny.contentStart, beautymail::templates.sunny.button

### Community 119 - "samples/ark.blade.php"
Cohesion: 0.50
Nodes (3): notify::emails.templates.ark.contentEnd, notify::emails.templates.ark.contentStart, notify::emails.templates.ark.heading

### Community 120 - "ark/mail.blade.php"
Cohesion: 0.50
Nodes (3): notify::emails.templates.ark.contentEnd, notify::emails.templates.ark.contentStart, notify::emails.templates.ark.heading

### Community 121 - "Test"
Cohesion: 0.67
Nodes (3): BackedEnum, Test, Modules\Xot\Filament\Clusters\XotBaseCluster

## Knowledge Gaps
- **177 isolated node(s):** `stylelint-config-standard`, `stylelint-config-prettier`, `color-no-invalid-hex`, `font-family-no-duplicate-names`, `font-family-no-missing-generic-family-keyword` (+172 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **47 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `TestCase` connect `TestCase` to `Illuminate\Database\Eloquent\Model`, `WhatsAppData`, `HasTenantNotifications.php`, `Spatie\QueueableAction\QueueableAction`, `NotificationTemplate`, `NotifyBasePolicy`, `TelegramData`, `SmtpData`, `NotificationLog.php`, `NotificationsCoverageTest.php`, `Modules\Xot\Filament\Pages\XotBasePage`, `MailTemplate.php`, `Illuminate\Support\Collection`, `SendRecordsNotificationAction.php`, `NotifyModelsCoverageTest.php`, `NotifyFilamentResourcesCoverageTest.php`, `NotifyThemeAndColumnsCoverageTest.php`, `NotifyTheme`, `Illuminate\Database\Eloquent\Factories\Factory`, `Modules\Notify\Contracts\SMS\SmsActionContract`, `BaseModel`, `Notification`, `NotificationManagementBusinessLogicTest.php`, `ThemeNotification`, `SendNotificationAction`, `NotifyDatasCoverageTest.php`, `config.php`, `Filament\Panel`, `Carbon\Carbon`, `NotifyServiceProvider.php`, `MediaTypeEnum.php`, `TelegramDriverEnum.php`, `WhatsAppDriverEnum.php`, `AttachmentData`, `HasContactDummyModel`, `EsendexSendAction.php`, `SendNotificationToRecipientAction.php`, `NotificationLogStatusEnum.php`, `SettingPage`, `EventServiceProvider`?**
  _High betweenness centrality (0.130) - this node is a cross-community bridge._
- **Why does `Notification` connect `Notification` to `Illuminate\Database\Eloquent\Model`, `Illuminate\Database\Seeder`, `NotificationTemplate`, `SmtpData`, `Modules\Xot\Filament\Pages\XotBasePage`, `Illuminate\Bus\Queueable`, `NotifyModelsCoverageTest.php`, `Illuminate\Database\Eloquent\Factories\Factory`, `Pest.php`, `NotificationManagementBusinessLogicTest.php`, `SendNotificationAction`, `NotificationData`, `SendPushNotification`, `NotificationResource.php`, `SendEmailPage`, `SendNetfunSmsPage`, `SendSmsPage`, `SendSpatieEmailPage`, `SendWhatsAppPage`, `SendEmail`, `SendTelegram`, `SendTelegramPage`, `SendNotificationToRecipientAction.php`?**
  _High betweenness centrality (0.033) - this node is a cross-community bridge._
- **Why does `NotificationTemplate` connect `NotificationTemplate` to `Illuminate\Database\Seeder`, `TestCase`, `BaseModel`, `Notification`, `NotificationManagementBusinessLogicTest.php`, `NotificationLog.php`, `SendNotificationAction`, `MailTemplate.php`, `NotifyModelsCoverageTest.php`, `NotifyFilamentResourcesCoverageTest.php`, `Illuminate\Database\Eloquent\Factories\Factory`?**
  _High betweenness centrality (0.024) - this node is a cross-community bridge._
- **What connects `stylelint-config-standard`, `stylelint-config-prettier`, `color-no-invalid-hex` to the rest of the system?**
  _177 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Illuminate\Database\Eloquent\Model` be split into smaller, more focused modules?**
  _Cohesion score 0.07439613526570048 - nodes in this community are weakly interconnected._
- **Should `Illuminate\Database\Seeder` be split into smaller, more focused modules?**
  _Cohesion score 0.057971014492753624 - nodes in this community are weakly interconnected._
- **Should `WhatsAppData` be split into smaller, more focused modules?**
  _Cohesion score 0.07171717171717172 - nodes in this community are weakly interconnected._
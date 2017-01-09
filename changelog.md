<a name="1.5.0"></a>
# [1.5.0](https://github.com/garyng/Mono/compare/v1.4.4...v1.5.0) (2017-01-09)


### Bug Fixes

* **WPF.CaMSys:** add PanningMode to ScrollViewer to support touchscreen ([72ae3d8](https://github.com/garyng/Mono/commit/72ae3d8))
* **WPF.Download:** add PanningMode to ScrollViewer to support touchscreen ([9714002](https://github.com/garyng/Mono/commit/9714002))
* **WPF.MMLS:** add PanningMode to ScrollViewer to support touchscreen ([95cda66](https://github.com/garyng/Mono/commit/95cda66))
* **WPF.Portal:** add PanningMode to ScrollViewer in PortalBulletinItemView to support touchscreen ([6adb7b3](https://github.com/garyng/Mono/commit/6adb7b3))
* **WPF.Portal:** add PanningMode to ScrollViewer to support touchscreen ([3ff0c84](https://github.com/garyng/Mono/commit/3ff0c84))
* **WPF.Settings:** add PanningMode to ScrollViewer to support touchscreen ([ea1b095](https://github.com/garyng/Mono/commit/ea1b095))
* **WPF.Settings:** remove "Accounts" section under Settings ([f711fb9](https://github.com/garyng/Mono/commit/f711fb9))
* **WPF.Settings:** remove ParserInfo and Account-related code ([e8dd67f](https://github.com/garyng/Mono/commit/e8dd67f))
* **WPF.Updater:** invoke noUpdates when IsInstalledApp is false ([8e06c36](https://github.com/garyng/Mono/commit/8e06c36))


### Features

* **WPF:** add Feedback button to PopupBox ([a2d41cb](https://github.com/garyng/Mono/commit/a2d41cb))
* **WPF:** autoclose sidebar when navigated to any of the page ([a4d76c4](https://github.com/garyng/Mono/commit/a4d76c4))
* **WPF.About:** add buttons to Facebook and GitHub ([109047d](https://github.com/garyng/Mono/commit/109047d))
* **WPF.CaMSys:** add toolbar to refresh and logout ([e10ed9a](https://github.com/garyng/Mono/commit/e10ed9a))
* **WPF.Controls:** press enter key to login in ParserLoginViewControl ([35ae6f8](https://github.com/garyng/Mono/commit/35ae6f8))
* **WPF.MMLS:** add toolbar to refresh and logout ([dddd974](https://github.com/garyng/Mono/commit/dddd974))
* **WPF.Portal:** add toolbar to refresh and logout ([e824358](https://github.com/garyng/Mono/commit/e824358))



<a name="1.4.4"></a>
## [1.4.4](https://github.com/garyng/Mono/compare/v1.4.3...v1.4.4) (2017-01-01)


### Bug Fixes

* **build:** don't increment build version after build ([e23d0d7](https://github.com/garyng/Mono/commit/e23d0d7))



<a name="1.4.3"></a>
## [1.4.3](https://github.com/garyng/Mono/compare/v1.4.2...v1.4.3) (2016-12-30)


### Bug Fixes

* change version styling in nupkg from x.x.x.x to x.x.x ([723a947](https://github.com/garyng/Mono/commit/723a947))



<a name="1.4.2"></a>
## [1.4.2](https://github.com/garyng/Mono/compare/v1.3.1752...v1.4.2) (2016-12-30)


### Bug Fixes

* **WPF.Portal:** hide LOAD MORE... button while searching ([865a1a6](https://github.com/garyng/Mono/commit/865a1a6))



<a name="1.3.1752"></a>
## [1.3.1752](https://github.com/garyng/Mono/compare/v1.2.1725...v1.3.1752) (2016-12-26)


### Bug Fixes

* **WPF.Faker:** fake the new IUpdater ([b2fd0ca](https://github.com/garyng/Mono/commit/b2fd0ca))
* **WPF.Settings:** set IsCheckingForUpdates to false after checking update ([e4f27e1](https://github.com/garyng/Mono/commit/e4f27e1))
* **WPF.Updater:** fix Version comparison ([98c3d56](https://github.com/garyng/Mono/commit/98c3d56))


### Features

* **WPF.Faker:** fake IUpdater ([55bf153](https://github.com/garyng/Mono/commit/55bf153))
* **WPF.Settings:** add noUpdates action ([8289de9](https://github.com/garyng/Mono/commit/8289de9))
* **WPF.Update:** add noUpdates action to Check() and CheckAndUpdate in IUpdater ([94cfc1a](https://github.com/garyng/Mono/commit/94cfc1a))



<a name="1.2.1725"></a>
## [1.2.1725](https://github.com/garyng/Mono/compare/v1.1.1718...v1.2.1725) (2016-12-24)


### Bug Fixes

* **WPF.About:** show the missing Mono.WPF version info due to change of assembly name ([a08d4c0](https://github.com/garyng/Mono/commit/a08d4c0))
* **WPF.Settings:** hide Restart button while checking update ([9631ab4](https://github.com/garyng/Mono/commit/9631ab4))



<a name="1.1.1718"></a>
## [1.1.1718](https://github.com/garyng/Mono/compare/v1.0.1708...v1.1.1718) (2016-12-24)


### Bug Fixes

* **WPF:** fix XAML exception while startup due to the change of the assembly name ([ac3d616](https://github.com/garyng/Mono/commit/ac3d616))
* **WPF:** rename AssemblyName from Mono.WPF to Mono ([4d062b8](https://github.com/garyng/Mono/commit/4d062b8))
* **WPF:** strip Revision from version while packing NuGet packages ([4f566bd](https://github.com/garyng/Mono/commit/4f566bd))
* **WPF.Module:** remove .SingleInstance() from IUpdater registration ([1254bcb](https://github.com/garyng/Mono/commit/1254bcb))
* **WPF.Settings:** request a Func<IUpdater> instead of IUpdater ([e9e0aa2](https://github.com/garyng/Mono/commit/e9e0aa2))



<a name="1.0.1708"></a>
## 1.0.1708 (2016-12-24)


### Bug Fixes

* **Core:** add rememberMe parameter to LoginAsync ([cc83aa5](https://github.com/garyng/Mono/commit/cc83aa5))
* **Core:** fix LoginAsync to support login with username and password ([753238a](https://github.com/garyng/Mono/commit/753238a))
* **Core:** prevent cache key name collision by prepending owner class name ([01572b3](https://github.com/garyng/Mono/commit/01572b3))
* **Core.CaMSys:** add _academicStatusParser when setting offline status ([8a670b6](https://github.com/garyng/Mono/commit/8a670b6))
* **Core.CaMSys:** add missing properties to ICaMSysParser ([d432715](https://github.com/garyng/Mono/commit/d432715))
* **Core.CaMSys:** fix not storing result into local StudentCenter property ([9824e37](https://github.com/garyng/Mono/commit/9824e37))
* **Core.CaMSys:** parse OutstandingCharge correctly ([c9776b4](https://github.com/garyng/Mono/commit/c9776b4))
* **Core.DataStorage:** use FileStream to read or wirte text asynchronously ([0f83ee8](https://github.com/garyng/Mono/commit/0f83ee8))
* **Core.Download:** catch potential IOException ([90d4a23](https://github.com/garyng/Mono/commit/90d4a23))
* **Core.Main:** change MainView button's font style weight to normal ([7493a3b](https://github.com/garyng/Mono/commit/7493a3b))
* **Core.MMLS:** sort WeekInfos by WeekNumber in MMLSCourseTimelineParser ([d8a0b08](https://github.com/garyng/Mono/commit/d8a0b08))
* **Core.MMLS:** trim leading tabs in MMLSCourseTimelineItem.WeekInfo.ContentInfo.Title ([885882d](https://github.com/garyng/Mono/commit/885882d))
* **Core.Portal:** remove HTML comments before parsing for content text ([5abde4a](https://github.com/garyng/Mono/commit/5abde4a))
* **Core.Portal:** remove unnecessary Task.Run in getAllBulletinItems ([5f79267](https://github.com/garyng/Mono/commit/5f79267))
* **Core.Portal:** uses HtmlDocumentExtensions ([061f28b](https://github.com/garyng/Mono/commit/061f28b))
* **WPF:** add Logo to MainView ([42ee620](https://github.com/garyng/Mono/commit/42ee620))
* **WPF:** add missing namespace to ParserViewModelBase ([0f0032e](https://github.com/garyng/Mono/commit/0f0032e))
* **WPF:** add NavigationService to ParserViewModelBase ([1e6fe0b](https://github.com/garyng/Mono/commit/1e6fe0b))
* **WPF:** change menu list item style ([46dd9af](https://github.com/garyng/Mono/commit/46dd9af))
* **WPF:** change PortalView from a Window to UserControl ([c3b9689](https://github.com/garyng/Mono/commit/c3b9689))
* **WPF:** fix Portal and PortalLogin view model to use new Navigated signature ([73cb57b](https://github.com/garyng/Mono/commit/73cb57b))
* **WPF:** fix wrongly registered type ([d55472f](https://github.com/garyng/Mono/commit/d55472f))
* **WPF:** let each view model override Title property ([a35568b](https://github.com/garyng/Mono/commit/a35568b))
* **WPF:** Main view now correctly show child view's title ([d9fac94](https://github.com/garyng/Mono/commit/d9fac94))
* **WPF:** register MMLSViewModel ([b9826df](https://github.com/garyng/Mono/commit/b9826df))
* **WPF:** register viewmodels as single instance ([244e247](https://github.com/garyng/Mono/commit/244e247))
* **WPF:** remove manual NavigatoinService registration code ([4e3affb](https://github.com/garyng/Mono/commit/4e3affb))
* **WPF:** remove margin for PortalView ([4f7e9b7](https://github.com/garyng/Mono/commit/4f7e9b7))
* **WPF:** rename MMLSViewModel to MMLSLoginView while resolving MMLSLoginViewModel ([69c1e3e](https://github.com/garyng/Mono/commit/69c1e3e))
* **WPF.CaMSys:** add missing CourseTerm in CaMSysCourseHistoryView ([c602432](https://github.com/garyng/Mono/commit/c602432))
* **WPF.CaMSys:** adjust Class Attandence's card margin in CaMSysView ([50c821a](https://github.com/garyng/Mono/commit/50c821a))
* **WPF.CaMSys:** set card to same height in CaMSysClassAttandenceView ([79b6748](https://github.com/garyng/Mono/commit/79b6748))
* **WPF.Converters:** prevent casting error in MultipleBooleanToVisibilityConverter ([58a1b39](https://github.com/garyng/Mono/commit/58a1b39))
* **WPF.Converters:** set properties of MultipleBooleanToVisibilityConverter when ProvideValue is called ([4efa6e9](https://github.com/garyng/Mono/commit/4efa6e9))
* **WPF.Faker:** add mising fake properties for ObservableDownloadItem ([c0b6205](https://github.com/garyng/Mono/commit/c0b6205))
* **WPF.Faker:** fake parameterized ObservableDownloadItem with .CustomInstantiator ([366be65](https://github.com/garyng/Mono/commit/366be65))
* **WPF.Faker:** fake PortalBulletinItem.Attachment's Filename ([9a1ec04](https://github.com/garyng/Mono/commit/9a1ec04))
* **WPF.Faker:** max 3 words for CourseDescription in FakeStudentCenter ([0a2d13a](https://github.com/garyng/Mono/commit/0a2d13a))
* **WPF.Faker:** use IDownloadItem instead of ObservableDownloadItem in FakeObservableDownloadItems ([9c2dd18](https://github.com/garyng/Mono/commit/9c2dd18))
* **WPF.Main:** change Listbox to ItemsControl with Buttons ([9f0a0a3](https://github.com/garyng/Mono/commit/9f0a0a3))
* **WPF.Module:** get the name of type TParser not the name of "TParser" in ParserModule ([c5e9d56](https://github.com/garyng/Mono/commit/c5e9d56))
* **WPF.Module:** remove unused parser-specific registration modules ([ba857c7](https://github.com/garyng/Mono/commit/ba857c7))
* **WPF.Modules:** register viewmodels with NavigationTargetAttribute as ViewModelBase ([80b5ec1](https://github.com/garyng/Mono/commit/80b5ec1))
* **WPF.Modules:** use FakeDataStorage while in design mode ([db3dbf7](https://github.com/garyng/Mono/commit/db3dbf7))
* **WPF.Portal:** add border around ListBoxItem ([a3ac76d](https://github.com/garyng/Mono/commit/a3ac76d))
* **WPF.Portal:** adjust margin in PortalBulletinItemView ([39b7df0](https://github.com/garyng/Mono/commit/39b7df0))
* **WPF.Portal:** change TextBlock margin to padding ([69ca9ed](https://github.com/garyng/Mono/commit/69ca9ed))
* **WPF.Portal:** hide "LOAD MORE..." when searching ([c9a7a64](https://github.com/garyng/Mono/commit/c9a7a64))
* **WPF.Portal:** hide "load more" button while searching ([ad55de7](https://github.com/garyng/Mono/commit/ad55de7))
* **WPF.Portal:** initialize _allPortalBulletinItems to prevent null exception ([bb777dd](https://github.com/garyng/Mono/commit/bb777dd))
* **WPF.Portal:** mouse over ListBoxItems will show a hand cursor ([639e3d7](https://github.com/garyng/Mono/commit/639e3d7))
* **WPF.Portal:** remove EventToCommand in PortalView and uses INavigationTarget ([0b94a4c](https://github.com/garyng/Mono/commit/0b94a4c))
* **WPF.Portal:** set Cursor to Hand at Grid instead of ListBoxItem ([4680b35](https://github.com/garyng/Mono/commit/4680b35))
* **WPF.Portal:** show "Nothing found..." when there is no search results ([0f843a6](https://github.com/garyng/Mono/commit/0f843a6))
* save logo file as Inkscape SVG file ([07a7b62](https://github.com/garyng/Mono/commit/07a7b62))
* **WPF.Portal:** still trying to hide "Load more..." button while searching ([998d107](https://github.com/garyng/Mono/commit/998d107))
* **WPF.Settings:** hide Restart button when not enabled in SettingsView ([ef078c3](https://github.com/garyng/Mono/commit/ef078c3))
* **WPF.Settings:** wire up LogoutCommand  to logout button in SettingsView ([ef3bb09](https://github.com/garyng/Mono/commit/ef3bb09))


### Features

* **Core:** add DataStorage ([e1a54af](https://github.com/garyng/Mono/commit/e1a54af))
* **Core:** add enum RequestMethod for IParserDataProvider ([621f565](https://github.com/garyng/Mono/commit/621f565))
* **Core:** add EnumerableExtensions ([9fa0fef](https://github.com/garyng/Mono/commit/9fa0fef))
* **Core:** add HtmlDocumentExtensions ([f65dfa2](https://github.com/garyng/Mono/commit/f65dfa2))
* **Core:** add IDataStorage ([0b31394](https://github.com/garyng/Mono/commit/0b31394))
* **Core:** add IOfflineable ([c9a9d50](https://github.com/garyng/Mono/commit/c9a9d50))
* **Core:** add IParserAccountCredentialsSaver ([cc15228](https://github.com/garyng/Mono/commit/cc15228))
* **Core:** add IParserAccountManager ([dca5fe7](https://github.com/garyng/Mono/commit/dca5fe7))
* **Core:** add IParserBase ([03f7cd5](https://github.com/garyng/Mono/commit/03f7cd5))
* **Core:** add IParserCacheManager ([82af01c](https://github.com/garyng/Mono/commit/82af01c))
* **Core:** add IParserCookieProvider and ParserCookieProvider ([d21d8ba](https://github.com/garyng/Mono/commit/d21d8ba))
* **Core:** add IParserDataProvider ([e9b6d05](https://github.com/garyng/Mono/commit/e9b6d05))
* **Core:** add IParserStateChangeObservable ([07677ff](https://github.com/garyng/Mono/commit/07677ff))
* **Core:** add IParserStateChangeObserver ([fc577e8](https://github.com/garyng/Mono/commit/fc577e8))
* **Core:** add IResultCacheable ([21ad64b](https://github.com/garyng/Mono/commit/21ad64b))
* **Core:** add method GetAllAssembliesVersion in Utilities ([12c584f](https://github.com/garyng/Mono/commit/12c584f))
* **Core:** add method in ParserCacheManager to delete cache from storage  ([d927cd9](https://github.com/garyng/Mono/commit/d927cd9))
* **Core:** add parser states ([5849a65](https://github.com/garyng/Mono/commit/5849a65))
* **Core:** add ParserAccountCredentials ([ef3d883](https://github.com/garyng/Mono/commit/ef3d883))
* **Core:** add ParserAccountCredentialsSaver ([3e56acf](https://github.com/garyng/Mono/commit/3e56acf))
* **Core:** add ParserAccountManagerBase ([9825663](https://github.com/garyng/Mono/commit/9825663))
* **Core:** add ParserBase ([b1214bb](https://github.com/garyng/Mono/commit/b1214bb))
* **Core:** add ParserChild ([9297c84](https://github.com/garyng/Mono/commit/9297c84))
* **Core:** add ParserHtmlDataCacheManager ([0347be2](https://github.com/garyng/Mono/commit/0347be2))
* **Core:** add ParserHtmlDataProvider ([b2f3b23](https://github.com/garyng/Mono/commit/b2f3b23))
* **Core:** add ParserStateBase ([a8848e9](https://github.com/garyng/Mono/commit/a8848e9))
* **Core:** add SelectSingleNodeText for parsing ([c694b28](https://github.com/garyng/Mono/commit/c694b28))
* **Core:** add TryParseToDouble method in StringExtensions ([12e8c6d](https://github.com/garyng/Mono/commit/12e8c6d))
* **Core:** add TryParseToInt to StringExtensions ([870705d](https://github.com/garyng/Mono/commit/870705d))
* **Core.CaMSys:** add CaMSysAcademicStatusParser ([40bf9bb](https://github.com/garyng/Mono/commit/40bf9bb))
* **Core.CaMSys:** add CaMSysClassAttendanceParser ([11b148d](https://github.com/garyng/Mono/commit/11b148d))
* **Core.CaMSys:** add CaMSysCourseHistoryParser ([79effa9](https://github.com/garyng/Mono/commit/79effa9))
* **Core.CaMSys:** add CaMSysDemographicInfoParser ([c662052](https://github.com/garyng/Mono/commit/c662052))
* **Core.CaMSys:** add CaMSysParserAccountManager ([3a49641](https://github.com/garyng/Mono/commit/3a49641))
* **Core.CaMSys:** add incomplete CaMSysClassScheduleParser ([e90d8eb](https://github.com/garyng/Mono/commit/e90d8eb))
* **Core.CaMSys:** add parser for StudentCenter ([ccf8c81](https://github.com/garyng/Mono/commit/ccf8c81))
* **Core.Download:** add DownloadItem states ([19aff0e](https://github.com/garyng/Mono/commit/19aff0e))
* **Core.Download:** add DownloadItemFactory ([792b420](https://github.com/garyng/Mono/commit/792b420))
* **Core.Download:** add FileAbsolutePath property ([bfc8dd6](https://github.com/garyng/Mono/commit/bfc8dd6))
* **Core.Download:** add GetAbsolutePath to DownloadItemBase ([3fe62e5](https://github.com/garyng/Mono/commit/3fe62e5))
* **Core.Download:** add IDownloadItem and incomplete DownloadItemBase ([d5f00d4](https://github.com/garyng/Mono/commit/d5f00d4))
* **Core.Download:** add IDownloadQueueManager and DownloadQueueManager ([055df64](https://github.com/garyng/Mono/commit/055df64))
* **Core.Download:** add Remove in IDownloadQueueManager ([ad20ab7](https://github.com/garyng/Mono/commit/ad20ab7))
* **Core.Download:** implement Download() in DownloadItemBase ([e575187](https://github.com/garyng/Mono/commit/e575187))
* **Core.Download:** support FileAbsolutePath ([207fabf](https://github.com/garyng/Mono/commit/207fabf))
* **Core.Extensions:** add DataProtectionExtensions ([96507df](https://github.com/garyng/Mono/commit/96507df))
* **Core.Extensions:** add SecureStringExtensions ([837d0a4](https://github.com/garyng/Mono/commit/837d0a4))
* **Core.MMLS:** add complete MMLSParser ([725e6dc](https://github.com/garyng/Mono/commit/725e6dc))
* **Core.Portal:** add IPortalParser  ([e1ef104](https://github.com/garyng/Mono/commit/e1ef104))
* **Core.Portal:** add PortalBulletinItemParser ([7e75a66](https://github.com/garyng/Mono/commit/7e75a66))
* **Core.Portal:** add PortalBulletinParser ([adeccd4](https://github.com/garyng/Mono/commit/adeccd4))
* **Core.Portal:** add PortalParser ([bc62200](https://github.com/garyng/Mono/commit/bc62200))
* **Core.Portal:** add PortalParserAccountManager  ([a9de095](https://github.com/garyng/Mono/commit/a9de095))
* **Core.Utilities:** Add Utilities ([d16d8f5](https://github.com/garyng/Mono/commit/d16d8f5))
* **Core.WPF:** add NegatedBooleanConverter ([de7b08c](https://github.com/garyng/Mono/commit/de7b08c))
* **WPF:** a better Navigated-related methods ([2646d71](https://github.com/garyng/Mono/commit/2646d71))
* **WPF:** add About view and view model ([381d6b1](https://github.com/garyng/Mono/commit/381d6b1))
* **WPF:** add BusyDialogView for showing progress ([6f4c5c3](https://github.com/garyng/Mono/commit/6f4c5c3))
* **WPF:** add FakeFactory for generating fake design time data ([ae85fd0](https://github.com/garyng/Mono/commit/ae85fd0))
* **WPF:** add FakeParserDataProvider ([f49f6b8](https://github.com/garyng/Mono/commit/f49f6b8))
* **WPF:** add generic ParserModule ([cae766b](https://github.com/garyng/Mono/commit/cae766b))
* **WPF:** add icon ([307fc8b](https://github.com/garyng/Mono/commit/307fc8b))
* **WPF:** add IDialogHostController and concrete implementation ([1136065](https://github.com/garyng/Mono/commit/1136065))
* **WPF:** add INavigationService ([720f440](https://github.com/garyng/Mono/commit/720f440))
* **WPF:** add INavigator ([c6fa459](https://github.com/garyng/Mono/commit/c6fa459))
* **WPF:** add isOffline to Module constructor ([65e772e](https://github.com/garyng/Mono/commit/65e772e))
* **WPF:** add logo resources ([2e3c714](https://github.com/garyng/Mono/commit/2e3c714))
* **WPF:** add MaterialDesignAccentTabablzControlStyle and MaterialDesignAccentDragableTabItemStyle ([5e30e74](https://github.com/garyng/Mono/commit/5e30e74))
* **WPF:** add my name in below main menu ([d987b38](https://github.com/garyng/Mono/commit/d987b38))
* **WPF:** add NavigationService ([0b6e1ac](https://github.com/garyng/Mono/commit/0b6e1ac))
* **WPF:** add NavigationTargetAttribute to view models ([4168cd4](https://github.com/garyng/Mono/commit/4168cd4))
* **WPF:** add PasswordBoxBindingBehaviour  ([4f52c18](https://github.com/garyng/Mono/commit/4f52c18))
* **WPF:** add PortalLogin view and view model ([fb190cb](https://github.com/garyng/Mono/commit/fb190cb))
* **WPF:** add SnackBar from XAML Material Design Toolkit ([a4ae050](https://github.com/garyng/Mono/commit/a4ae050))
* **WPF:** add ViewModelLocator ([215c719](https://github.com/garyng/Mono/commit/215c719))
* **WPF:** add views to sidebar lists ([3519731](https://github.com/garyng/Mono/commit/3519731))
* **WPF:** import Dragablz Material Design style ([af1978b](https://github.com/garyng/Mono/commit/af1978b))
* **WPF:** register CaMSys parser ([5c0b6a0](https://github.com/garyng/Mono/commit/5c0b6a0))
* **WPF:** register NavigationServiceModule ([00bdcff](https://github.com/garyng/Mono/commit/00bdcff))
* **WPF:** register NavigationTargetAutoRegistrar into IoC ([c08033e](https://github.com/garyng/Mono/commit/c08033e))
* **WPF:** subclass MVVMLight's ViewModelBase ([1865d57](https://github.com/garyng/Mono/commit/1865d57))
* **WPF:** use IDialogHostController in Main ([8ad0816](https://github.com/garyng/Mono/commit/8ad0816))
* **WPF:** uses NavigationHeaderCard ([9dbf4cb](https://github.com/garyng/Mono/commit/9dbf4cb))
* **WPF:** uses new navigation methods in Portal and PortalLogin view model  ([f133cc5](https://github.com/garyng/Mono/commit/f133cc5))
* **WPF.About:** add About view and viewmodel ([49fd385](https://github.com/garyng/Mono/commit/49fd385))
* **WPF.Behaviours:** add IgnoreMouseWheelBehaviour ([cb54bcc](https://github.com/garyng/Mono/commit/cb54bcc))
* **WPF.CaMSts:** add property CaMSysClassSchedule ([516887a](https://github.com/garyng/Mono/commit/516887a))
* **WPF.CaMSys:** add binding properties to CaMSysViewModel ([c0f5b77](https://github.com/garyng/Mono/commit/c0f5b77))
* **WPF.CaMSys:** add CaMSys and CaMSys login views and view model ([7ccbe09](https://github.com/garyng/Mono/commit/7ccbe09))
* **WPF.CaMSys:** add CaMSysClassAttandence view and view model ([5dd21bc](https://github.com/garyng/Mono/commit/5dd21bc))
* **WPF.CaMSys:** add CaMSysCourseHistory view and viewmodel ([abc2589](https://github.com/garyng/Mono/commit/abc2589))
* **WPF.CaMSys:** add cards for student info and course history ([9592cb1](https://github.com/garyng/Mono/commit/9592cb1))
* **WPF.CaMSys:** add Class Attendance card ([4814ba8](https://github.com/garyng/Mono/commit/4814ba8))
* **WPF.CaMSys:** add placeholder for class schedule ([851e338](https://github.com/garyng/Mono/commit/851e338))
* **WPF.CaMSys:** add search to CaMSysCourseHistory view and viewmodel ([28b81bb](https://github.com/garyng/Mono/commit/28b81bb))
* **WPF.Controls:** add EmptyStateControl ([13f16ce](https://github.com/garyng/Mono/commit/13f16ce))
* **WPF.Controls:** add NavigationHeaderCard ([ea07d6c](https://github.com/garyng/Mono/commit/ea07d6c))
* **WPF.Controls:** add RetryButtonVisibility dependency property to control the visibility of the Retry button ([0bfa4fb](https://github.com/garyng/Mono/commit/0bfa4fb))
* **WPF.Controls:** add UniformWrapPanel  ([2526ac7](https://github.com/garyng/Mono/commit/2526ac7))
* **WPF.Controls:** add ViewActionCard ([7ecc646](https://github.com/garyng/Mono/commit/7ecc646))
* **WPF.Converters:** add FilenameToExtensionConverter ([541c601](https://github.com/garyng/Mono/commit/541c601))
* **WPF.Converters:** add MultipleBooleanToVisibilityConverter ([fddd0cb](https://github.com/garyng/Mono/commit/fddd0cb))
* **WPF.Converters:** add ReadableBytesConverter ([4de6764](https://github.com/garyng/Mono/commit/4de6764))
* **WPF.Download:** add ContentLength property in ObservableDownloadItem ([96f72f4](https://github.com/garyng/Mono/commit/96f72f4))
* **WPF.Download:** add DownloadItemControl ([d715df5](https://github.com/garyng/Mono/commit/d715df5))
* **WPF.Download:** add Downloads view and view model ([64b85b4](https://github.com/garyng/Mono/commit/64b85b4))
* **WPF.Download:** add ObservableDownloadItem ([e2e4174](https://github.com/garyng/Mono/commit/e2e4174))
* **WPF.Download:** change ObservableDownloadItem construtor signature ([f50763c](https://github.com/garyng/Mono/commit/f50763c))
* **WPF.Download:** support FileAbsolutePath ([4678a00](https://github.com/garyng/Mono/commit/4678a00))
* **WPF.Extensions:** add ToObservableCollection in EnumerableExtensions ([17e55b3](https://github.com/garyng/Mono/commit/17e55b3))
* **WPF.Faker:** add FakeDataStorage ([620a386](https://github.com/garyng/Mono/commit/620a386))
* **WPF.Faker:** add FakeDownloadItem ([002b3f2](https://github.com/garyng/Mono/commit/002b3f2))
* **WPF.Faker:** add FakeMMLS ([0f953b6](https://github.com/garyng/Mono/commit/0f953b6))
* **WPF.Faker:** add FakeObservableUserSettings under FakeUserSettings ([b5da948](https://github.com/garyng/Mono/commit/b5da948))
* **WPF.Faker:** add faker for CaMSysClassSchedule ([1ab8f08](https://github.com/garyng/Mono/commit/1ab8f08))
* **WPF.Faker:** add fakes for FakeCaMSys ([767aa8f](https://github.com/garyng/Mono/commit/767aa8f))
* **WPF.Faker:** add FakeStudentCenter ([da21a06](https://github.com/garyng/Mono/commit/da21a06))
* **WPF.Faker:** add FakeUpdater ([91d38f5](https://github.com/garyng/Mono/commit/91d38f5))
* **WPF.MMLS:** add MMLSAttachmentInfoButton ([0572db9](https://github.com/garyng/Mono/commit/0572db9))
* **WPF.MMLS:** add MMLSContentInfosControl ([7a2f7cf](https://github.com/garyng/Mono/commit/7a2f7cf))
* **WPF.MMLS:** add MMLSCourseTimelineItemControl view and view model ([0f4b9a9](https://github.com/garyng/Mono/commit/0f4b9a9))
* **WPF.MMLS:** complete MMLS view and viewmodel ([ee95da7](https://github.com/garyng/Mono/commit/ee95da7))
* **WPF.MMLS:** get DownloadFolder with ISettingsProvider ([6d9a100](https://github.com/garyng/Mono/commit/6d9a100))
* **WPF.MMLS:** implement DownloadAttachmentCommand ([37694fc](https://github.com/garyng/Mono/commit/37694fc))
* **WPF.MMLS:** replace MMLSAttachmentInfoButton with generic AttachmentInfoButton ([daa9026](https://github.com/garyng/Mono/commit/daa9026))
* **WPF.Module:** add .WithAttributeFilter() to view model registrations ([d70914f](https://github.com/garyng/Mono/commit/d70914f))
* **WPF.Module:** add UpdaterModule ([fb0dc7f](https://github.com/garyng/Mono/commit/fb0dc7f))
* **WPF.Module:** register DownloadItemFactory in ParserModule ([79ddebe](https://github.com/garyng/Mono/commit/79ddebe))
* **WPF.Module:** register DownloadQueueManager ([cb233f3](https://github.com/garyng/Mono/commit/cb233f3))
* **WPF.Module:** uses ParserModule in ViewModelLocator ([a946359](https://github.com/garyng/Mono/commit/a946359))
* **WPF.Modules:** register view models with Autofac's type scanning ([60a03e5](https://github.com/garyng/Mono/commit/60a03e5))
* **WPF.Navigation:** add flags to notify view model navigation type ([a897fa7](https://github.com/garyng/Mono/commit/a897fa7))
* **WPF.Navigation:** add GoTo method with custom action to setup the view model ([ad6542f](https://github.com/garyng/Mono/commit/ad6542f))
* **WPF.Navigation:** add INavigationTarget ([eb7130d](https://github.com/garyng/Mono/commit/eb7130d))
* **WPF.Navigation:** add NavigationTargetAttribute ([ccf9621](https://github.com/garyng/Mono/commit/ccf9621))
* **WPF.Navigation:** add NavigationTargetAutoRegistrar ([0e3de69](https://github.com/garyng/Mono/commit/0e3de69))
* **WPF.Navigation:** add pending list for registration while there is no INavigator subscribed ([8285d95](https://github.com/garyng/Mono/commit/8285d95))
* **WPF.Navigation:** INavigationService can navigate to a given type of T ([f495d9a](https://github.com/garyng/Mono/commit/f495d9a))
* **WPF.Navigation:** notify Navigator when CanGoBack or CanGoForward changed ([10e9447](https://github.com/garyng/Mono/commit/10e9447))
* **WPF.Navigation:** support IsFullscreen property ([0ba7b99](https://github.com/garyng/Mono/commit/0ba7b99))
* **WPF.Portal:** add IsSearching binding property ([6b5b2bb](https://github.com/garyng/Mono/commit/6b5b2bb))
* **WPF.Portal:** add plain text view in PortalBulletinItemView ([3f3ad5c](https://github.com/garyng/Mono/commit/3f3ad5c))
* **WPF.Portal:** add views and viewmodels for showing bulletin item details ([f808971](https://github.com/garyng/Mono/commit/f808971))
* **WPF.Portal:** better PortalBulletinItemView ([7e6f0ec](https://github.com/garyng/Mono/commit/7e6f0ec))
* **WPF.Portal:** change PortalBulletinItemAttachmentButton to AttachmentInfoButton ([2f624dc](https://github.com/garyng/Mono/commit/2f624dc))
* **WPF.Portal:** complete portal login logic ([0391c08](https://github.com/garyng/Mono/commit/0391c08))
* **WPF.Portal:** get DownloadFolder with ISettingsProvider ([69b73c6](https://github.com/garyng/Mono/commit/69b73c6))
* **WPF.Portal:** Portal view now can display parsed result ([5875c2c](https://github.com/garyng/Mono/commit/5875c2c))
* **WPF.Portal:** show EmptyStateControl when parsing failed ([2fbd2e4](https://github.com/garyng/Mono/commit/2fbd2e4))
* **WPF.Settings:** add ISettingsProvider and SettingsProviderBase ([90b63c5](https://github.com/garyng/Mono/commit/90b63c5))
* **WPF.Settings:** add IUserSettings and UserSettingsBase ([f7a8633](https://github.com/garyng/Mono/commit/f7a8633))
* **WPF.Settings:** add ObservableSettingsProvider ([1f06447](https://github.com/garyng/Mono/commit/1f06447))
* **WPF.Settings:** add ObservableUserSettings ([ea35407](https://github.com/garyng/Mono/commit/ea35407))
* **WPF.Settings:** add ParserInfo ([fa5c855](https://github.com/garyng/Mono/commit/fa5c855))
* **WPF.Settings:** add Settings view and view model ([0db3b70](https://github.com/garyng/Mono/commit/0db3b70))
* **WPF.Settings:** supprt update checking ([65daedc](https://github.com/garyng/Mono/commit/65daedc))
* **WPF.Update:** add IUpdater and Updater ([61d6632](https://github.com/garyng/Mono/commit/61d6632))




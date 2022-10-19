```
-------------------------------------
Translated Report (Full Report Below)
-------------------------------------

Process:               Xcodes [26133]
Path:                  /Applications/Xcodes.app/Contents/MacOS/Xcodes
Identifier:            com.robotsandpencils.XcodesApp
Version:               1.8.0 (16)
Code Type:             X86-64 (Native)
Parent Process:        launchd [1]
User ID:               501

Date/Time:             2022-10-19 14:35:58.9474 +0800
OS Version:            macOS 12.6 (21G115)
Report Version:        12
Bridge OS Version:     6.6 (19P6067)
Anonymous UUID:        F24E6CF7-FE19-3EDC-73C9-79E00D87575A


Time Awake Since Boot: 20000 seconds

System Integrity Protection: enabled

Crashed Thread:        0  Dispatch queue: com.apple.main-thread

Exception Type:        EXC_CRASH (SIGABRT)
Exception Codes:       0x0000000000000000, 0x0000000000000000
Exception Note:        EXC_CORPSE_NOTIFY

Application Specific Information:
abort() called


Thread 0 Crashed::  Dispatch queue: com.apple.main-thread
0   libsystem_kernel.dylib        	    0x7ff81366a00e __pthread_kill + 10
1   libsystem_pthread.dylib       	    0x7ff8136a01ff pthread_kill + 263
2   libsystem_c.dylib             	    0x7ff8135ebd24 abort + 123
3   libswiftCore.dylib            	    0x7ff820e4dbec swift::fatalError(unsigned int, char const*, ...) + 252
4   libswiftCore.dylib            	    0x7ff820e4e2c6 swift::runtime::AccessSet::insert(swift::runtime::Access*, void*, void*, swift::ExclusivityFlags) + 582
5   libswiftCore.dylib            	    0x7ff820e4e322 swift_beginAccess + 66
6   SwiftUI                       	    0x7ff91f70f1d8 NSViewResponder.addContentPath(to:kind:in:observer:) + 66
7   SwiftUI                       	    0x7ff91edcc461 AccessibilityGeometryStorage.updatePath() + 814
8   SwiftUI                       	    0x7ff91edcc0d5 AccessibilityGeometryStorage.path.getter + 29
9   SwiftUI                       	    0x7ff91f63ac08 AccessibilityNode.contentPath.getter + 194
10  SwiftUI                       	    0x7ff91f63eb48 AccessibilityNode.contentFrameFromPath.getter + 36
11  SwiftUI                       	    0x7ff91f63ecb3 AccessibilityNode.contentFrame.getter + 141
12  SwiftUI                       	    0x7ff91f6ac30c closure #1 in Sequence<>.sorted(with:) + 124
13  SwiftUI                       	    0x7ff91ef0840a specialized MutableCollection<>._insertionSort(within:sortedEnd:by:) + 128
14  SwiftUI                       	    0x7ff91ef0813b specialized UnsafeMutableBufferPointer._stableSortImpl(by:) + 1661
15  SwiftUI                       	    0x7ff91ef063fb specialized MutableCollection<>.sort(by:) + 90
16  SwiftUI                       	    0x7ff91f7c4f34 static Accessibility.queryChildren(element:options:) + 267
17  SwiftUI                       	    0x7ff91f567523 static Accessibility.queryPlatformChildren(element:options:) + 93
18  SwiftUI                       	    0x7ff91f621036 AccessibilityNode.accessibilityChildren() + 17
19  SwiftUI                       	    0x7ff91f620fd0 @objc AccessibilityNode.accessibilityChildrenInNavigationOrder() + 31
20  AppKit                        	    0x7ff81623ae3e -[NSAccessibilityAttributeAccessorInfo getAttributeValue:forObject:] + 58
21  AppKit                        	    0x7ff8167ab1de ___NSAccessibilityEntryPointValueForAttribute_block_invoke.818 + 1435
22  AppKit                        	    0x7ff8167a6cdc NSAccessibilityPerformEntryPointObject + 16
23  AppKit                        	    0x7ff816475f1f _NSAccessibilityEntryPointValueForAttribute + 168
24  AppKit                        	    0x7ff81623ac05 NSAccessibilityChildren + 41
25  AppKit                        	    0x7ff81623c4b0 NSAccessibilityUnignoredChildren + 216
26  SwiftUI                       	    0x7ff91f5672fc static Accessibility.queryPlatformFilter(elements:options:) + 393
27  SwiftUI                       	    0x7ff91f70da4d NSHostingView.appKitAccessibilityChildren(options:) + 25
28  SwiftUI                       	    0x7ff91f7162cc NSHostingView.accessibilityChildren() + 14
29  SwiftUI                       	    0x7ff91f716302 @objc NSHostingView.accessibilityChildren() + 24
30  AppKit                        	    0x7ff81623ae3e -[NSAccessibilityAttributeAccessorInfo getAttributeValue:forObject:] + 58
31  AppKit                        	    0x7ff8167ab1de ___NSAccessibilityEntryPointValueForAttribute_block_invoke.818 + 1435
32  AppKit                        	    0x7ff8167a6cdc NSAccessibilityPerformEntryPointObject + 16
33  AppKit                        	    0x7ff816475f1f _NSAccessibilityEntryPointValueForAttribute + 168
34  AppKit                        	    0x7ff81623ac05 NSAccessibilityChildren + 41
35  AppKit                        	    0x7ff81623c4b0 NSAccessibilityUnignoredChildren + 216
36  AppKit                        	    0x7ff81623c2bc NSAccessibilityGetObjectForAttributeUsingLegacyAPI + 337
37  AppKit                        	    0x7ff81623bd66 NSAccessibilityGetObjectValueForAttribute + 2718
38  AppKit                        	    0x7ff81623ae3e -[NSAccessibilityAttributeAccessorInfo getAttributeValue:forObject:] + 58
39  AppKit                        	    0x7ff8167ab1de ___NSAccessibilityEntryPointValueForAttribute_block_invoke.818 + 1435
40  AppKit                        	    0x7ff8167a6cdc NSAccessibilityPerformEntryPointObject + 16
41  AppKit                        	    0x7ff816475f1f _NSAccessibilityEntryPointValueForAttribute + 168
42  AppKit                        	    0x7ff81623ac05 NSAccessibilityChildren + 41
43  AppKit                        	    0x7ff81623c4b0 NSAccessibilityUnignoredChildren + 216
44  AppKit                        	    0x7ff816940db1 -[NSTableViewCellMockElement accessibilityChildrenAttribute] + 115
45  AppKit                        	    0x7ff81623c2bc NSAccessibilityGetObjectForAttributeUsingLegacyAPI + 337
46  AppKit                        	    0x7ff8167ab66b ___NSAccessibilityEntryPointValueForAttribute_block_invoke.818 + 2600
47  AppKit                        	    0x7ff8167a6cdc NSAccessibilityPerformEntryPointObject + 16
48  AppKit                        	    0x7ff816475f1f _NSAccessibilityEntryPointValueForAttribute + 168
49  AppKit                        	    0x7ff81623ac05 NSAccessibilityChildren + 41
50  AppKit                        	    0x7ff8163764a8 -[NSObject(NSObjectAccessibilityAttributeAccessAdditions) accessibilityIndexOfChild:] + 14
51  AppKit                        	    0x7ff816376362 -[NSObject(NSAccessibilityUIElementSpecifier) _accessibilityUIElementSpecifierForChild:registerIfNeeded:] + 134
52  AppKit                        	    0x7ff81632f13e -[NSObject(NSAccessibilityUIElementSpecifier) _accessibilityUIElementSpecifierRegisterIfNeeded:] + 146
53  AppKit                        	    0x7ff816476e99 NSAccessibilityPostNotificationForObservedElementWithUserInfo + 440
54  SwiftUI                       	    0x7ff91f568115 Accessibility.Notification.Info.post(name:) + 765
55  SwiftUI                       	    0x7ff91edcdec9 AccessibilityGeometryStorage.contentPathDidChange() + 170
56  SwiftUI                       	    0x7ff91edcdf4a AccessibilityGeometryStorage.PathObserver.contentPathDidChange() + 29
57  SwiftUI                       	    0x7ff91ecd0d9b ContentPathObservers.notify() + 123
58  SwiftUI                       	    0x7ff91f4021ce specialized ViewResponderFilter.updateValue() + 504
59  SwiftUI                       	    0x7ff91f43ee3e partial apply for specialized implicit closure #2 in implicit closure #1 in closure #1 in closure #1 in Attribute.init<A>(_:) + 32
60  AttributeGraph                	    0x7ff91face757 AG::Graph::UpdateStack::update() + 559
61  AttributeGraph                	    0x7ff91faced57 AG::Graph::update_attribute(AG::data::ptr<AG::Node>, unsigned int) + 421
62  AttributeGraph                	    0x7ff91fad4dad AG::Graph::value_ref(AG::AttributeID, AGSwiftMetadata const*, unsigned char&) + 155
63  AttributeGraph                	    0x7ff91faeba5f AGGraphGetValue + 289
64  SwiftUI                       	    0x7ff91eeafd31 ViewGraph.updateRequestedOutputs() + 239
65  SwiftUI                       	    0x7ff91eeaf930 ViewGraph.updateOutputs() + 354
66  SwiftUI                       	    0x7ff91f6c7676 closure #1 in ViewRendererHost.render(interval:updateDisplayList:) + 2065
67  SwiftUI                       	    0x7ff91f6b2b31 ViewRendererHost.render(interval:updateDisplayList:) + 374
68  SwiftUI                       	    0x7ff91f712586 closure #1 in NSHostingView.layout() + 126
69  SwiftUI                       	    0x7ff91f71b744 partial apply for thunk for @callee_guaranteed (@guaranteed NSAnimationContext) -> () + 17
70  SwiftUI                       	    0x7ff91f70fb74 thunk for @escaping @callee_guaranteed (@guaranteed NSAnimationContext) -> () + 40
71  AppKit                        	    0x7ff8161ba1ab +[NSAnimationContext runAnimationGroup:] + 55
72  SwiftUI                       	    0x7ff91f7124ba NSHostingView.layout() + 287
73  SwiftUI                       	    0x7ff91f7128ba @objc NSHostingView.layout() + 21
74  AppKit                        	    0x7ff8161f5a94 _NSViewLayout + 564
75  AppKit                        	    0x7ff8161f5573 -[NSView _layoutSubtreeWithOldSize:] + 361
76  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
77  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
78  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
79  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
80  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
81  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
82  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
83  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
84  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
85  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
86  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
87  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
88  AppKit                        	    0x7ff8161f56c1 -[NSView _layoutSubtreeWithOldSize:] + 695
89  AppKit                        	    0x7ff8161f4a85 -[NSView _layoutSubtreeIfNeededAndAllowTemporaryEngine:] + 1041
90  AppKit                        	    0x7ff8161f457d -[NSWindow(NSConstraintBasedLayout) _layoutViewTree] + 148
91  AppKit                        	    0x7ff81626ae8d -[NSWindow(NSConstraintBasedLayout) layoutIfNeeded] + 251
92  AppKit                        	    0x7ff81626accc __NSWindowGetDisplayCycleObserverForLayout_block_invoke + 430
93  AppKit                        	    0x7ff816269f57 NSDisplayCycleObserverInvoke + 155
94  AppKit                        	    0x7ff816269ae4 NSDisplayCycleFlush + 921
95  QuartzCore                    	    0x7ff81a817fbe CA::Transaction::run_commit_handlers(CATransactionPhase) + 98
96  QuartzCore                    	    0x7ff81a816cdc CA::Transaction::commit() + 376
97  AppKit                        	    0x7ff81630b1d1 __62+[CATransaction(NSCATransaction) NS_setFlushesWithDisplayLink]_block_invoke + 285
98  AppKit                        	    0x7ff816a52f5c ___NSRunLoopObserverCreateWithHandler_block_invoke + 41
99  CoreFoundation                	    0x7ff813766520 __CFRUNLOOP_IS_CALLING_OUT_TO_AN_OBSERVER_CALLBACK_FUNCTION__ + 23
100 CoreFoundation                	    0x7ff8137663b2 __CFRunLoopDoObservers + 543
101 CoreFoundation                	    0x7ff813765844 __CFRunLoopRun + 840
102 CoreFoundation                	    0x7ff813764e3c CFRunLoopRunSpecific + 562
103 HIToolbox                     	    0x7ff81c4145e6 RunCurrentEventLoopInMode + 292
104 HIToolbox                     	    0x7ff81c414213 ReceiveNextEventCommon + 283
105 HIToolbox                     	    0x7ff81c4140e5 _BlockUntilNextEventMatchingListInModeWithFilter + 70
106 AppKit                        	    0x7ff81619efad _DPSNextEvent + 927
107 AppKit                        	    0x7ff81619d66a -[NSApplication(NSEvent) _nextEventMatchingEventMask:untilDate:inMode:dequeue:] + 1394
108 AppKit                        	    0x7ff81618fd19 -[NSApplication run] + 586
109 AppKit                        	    0x7ff816163c97 NSApplicationMain + 817
110 SwiftUI                       	    0x7ff91eca509c specialized runApp(_:) + 161
111 SwiftUI                       	    0x7ff91f707424 runApp<A>(_:) + 164
112 SwiftUI                       	    0x7ff91f1ffc5f static App.main() + 63
113 Xcodes                        	       0x1053635f1 0x105361000 + 9713
114 dyld                          	       0x1110e752e start + 462

Thread 1:: com.apple.NSEventThread
0   libsystem_kernel.dylib        	    0x7ff81366397a mach_msg_trap + 10
1   libsystem_kernel.dylib        	    0x7ff813663ce8 mach_msg + 56
2   CoreFoundation                	    0x7ff81376736d __CFRunLoopServiceMachPort + 319
3   CoreFoundation                	    0x7ff8137659f8 __CFRunLoopRun + 1276
4   CoreFoundation                	    0x7ff813764e3c CFRunLoopRunSpecific + 562
5   AppKit                        	    0x7ff81630c9ce _NSEventThread + 132
6   libsystem_pthread.dylib       	    0x7ff8136a04e1 _pthread_start + 125
7   libsystem_pthread.dylib       	    0x7ff81369bf6b thread_start + 15

Thread 2:: com.apple.NSURLConnectionLoader
0   libsystem_kernel.dylib        	    0x7ff81366397a mach_msg_trap + 10
1   libsystem_kernel.dylib        	    0x7ff813663ce8 mach_msg + 56
2   CoreFoundation                	    0x7ff81376736d __CFRunLoopServiceMachPort + 319
3   CoreFoundation                	    0x7ff8137659f8 __CFRunLoopRun + 1276
4   CoreFoundation                	    0x7ff813764e3c CFRunLoopRunSpecific + 562
5   CFNetwork                     	    0x7ff81838f7ec 0x7ff818146000 + 2398188
6   Foundation                    	    0x7ff8145bb994 __NSThread__start__ + 1009
7   libsystem_pthread.dylib       	    0x7ff8136a04e1 _pthread_start + 125
8   libsystem_pthread.dylib       	    0x7ff81369bf6b thread_start + 15

Thread 3::  Dispatch queue: com.apple.root.default-qos
0   libsystem_kernel.dylib        	    0x7ff81366397a mach_msg_trap + 10
1   libsystem_kernel.dylib        	    0x7ff813663ce8 mach_msg + 56
2   CoreFoundation                	    0x7ff81376736d __CFRunLoopServiceMachPort + 319
3   CoreFoundation                	    0x7ff8137659f8 __CFRunLoopRun + 1276
4   CoreFoundation                	    0x7ff813764e3c CFRunLoopRunSpecific + 562
5   Foundation                    	    0x7ff81464f50e -[NSConcreteTask waitUntilExit] + 332
6   Xcodes                        	       0x1053e510f 0x105361000 + 540943
7   Xcodes                        	       0x1053e5b65 0x105361000 + 543589
8   Xcodes                        	       0x105365409 0x105361000 + 17417
9   libdispatch.dylib             	    0x7ff8134e80cc _dispatch_call_block_and_release + 12
10  libdispatch.dylib             	    0x7ff8134e9317 _dispatch_client_callout + 8
11  libdispatch.dylib             	    0x7ff8134eb9fc _dispatch_queue_override_invoke + 787
12  libdispatch.dylib             	    0x7ff8134f8ac2 _dispatch_root_queue_drain + 343
13  libdispatch.dylib             	    0x7ff8134f925c _dispatch_worker_thread2 + 160
14  libsystem_pthread.dylib       	    0x7ff81369cf8a _pthread_wqthread + 256
15  libsystem_pthread.dylib       	    0x7ff81369bf57 start_wqthread + 15

Thread 4:
0   libsystem_pthread.dylib       	    0x7ff81369bf48 start_wqthread + 0

Thread 5:
0   libsystem_pthread.dylib       	    0x7ff81369bf48 start_wqthread + 0

Thread 6:
0   libsystem_pthread.dylib       	    0x7ff81369bf48 start_wqthread + 0


Thread 0 crashed with X86 Thread State (64-bit):
  rax: 0x0000000000000000  rbx: 0x0000000111162600  rcx: 0x00007ff7bab99228  rdx: 0x0000000000000000
  rdi: 0x0000000000000103  rsi: 0x0000000000000006  rbp: 0x00007ff7bab99250  rsp: 0x00007ff7bab99228
   r8: 0x0000b88b3c1e0ff0   r9: 0x000000000000ffff  r10: 0x0000000000000000  r11: 0x0000000000000246
  r12: 0x0000000000000103  r13: 0x00007ff854e17990  r14: 0x0000000000000006  r15: 0x0000000000000016
  rip: 0x00007ff81366a00e  rfl: 0x0000000000000246  cr2: 0x00007ff854df4ea8
  
Logical CPU:     0
Error Code:      0x02000148 
Trap Number:     133


Binary Images:
    0x7ff813662000 -     0x7ff813699fff libsystem_kernel.dylib (*) <8cc28466-fd2f-3c80-9834-9525b7beac19> /usr/lib/system/libsystem_kernel.dylib
    0x7ff81369a000 -     0x7ff8136a5fff libsystem_pthread.dylib (*) <b5454e27-e8c7-3fdb-b77f-714f1e82e70b> /usr/lib/system/libsystem_pthread.dylib
    0x7ff81356a000 -     0x7ff8135f2fff libsystem_c.dylib (*) <e42e9d7a-03b4-340b-b61e-dcd45fd4acc0> /usr/lib/system/libsystem_c.dylib
    0x7ff820b53000 -     0x7ff820fccfff libswiftCore.dylib (*) <9b8f4225-6ea3-313c-b5b2-7b594e2d1ef1> /usr/lib/swift/libswiftCore.dylib
    0x7ff91ec29000 -     0x7ff91fac8fff com.apple.SwiftUI (3.5.2) <c9ddd0f6-537b-305a-9175-8e6b4e748028> /System/Library/Frameworks/SwiftUI.framework/Versions/A/SwiftUI
    0x7ff816160000 -     0x7ff816feffff com.apple.AppKit (6.9) <06015263-62ac-3b08-a298-dc835c18452a> /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
    0x7ff91fac9000 -     0x7ff91fafffff com.apple.AttributeGraph (3.2.1) <06f5a511-e357-3dad-83c8-74bd8fc16b91> /System/Library/PrivateFrameworks/AttributeGraph.framework/Versions/A/AttributeGraph
    0x7ff81a814000 -     0x7ff81ab26fff com.apple.QuartzCore (1.11) <fe25fa55-548b-3a42-84bb-31b16eace40e> /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
    0x7ff8136e7000 -     0x7ff813be9fff com.apple.CoreFoundation (6.9) <93c48919-68af-367e-9a67-db4159bc962c> /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
    0x7ff81c3e6000 -     0x7ff81c6d9fff com.apple.HIToolbox (2.1.1) <06fdecd6-9f69-397b-b1e2-a8226c0ba7ed> /System/Library/Frameworks/Carbon.framework/Versions/A/Frameworks/HIToolbox.framework/Versions/A/HIToolbox
       0x105361000 -        0x105538fff com.robotsandpencils.XcodesApp (1.8.0) <910f86fa-9767-33a5-a170-248c0c6493f2> /Applications/Xcodes.app/Contents/MacOS/Xcodes
       0x1110e2000 -        0x11114dfff dyld (*) <71febccd-d9dc-3599-9971-2b3407c588a8> /usr/lib/dyld
    0x7ff818146000 -     0x7ff8185d5fff com.apple.CFNetwork (1335.0.3) <e9a42d7f-04b9-3d22-ace5-46a1c2ecace7> /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
    0x7ff814563000 -     0x7ff81491ffff com.apple.Foundation (6.9) <e22e60bb-ab77-3120-862f-92fa74feffcf> /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
    0x7ff8134e6000 -     0x7ff81352cfff libdispatch.dylib (*) <1a04b380-76e4-3e4b-b0fc-9837533d021d> /usr/lib/system/libdispatch.dylib

External Modification Summary:
  Calls made by other processes targeting this process:
    task_for_pid: 0
    thread_create: 0
    thread_set_state: 0
  Calls made by this process:
    task_for_pid: 0
    thread_create: 0
    thread_set_state: 0
  Calls made by all processes on this machine:
    task_for_pid: 6
    thread_create: 0
    thread_set_state: 0

VM Region Summary:
ReadOnly portion of Libraries: Total=1.1G resident=0K(0%) swapped_out_or_unallocated=1.1G(100%)
Writable regions: Total=622.5M written=0K(0%) resident=0K(0%) swapped_out=0K(0%) unallocated=622.5M(100%)

                                VIRTUAL   REGION 
REGION TYPE                        SIZE    COUNT (non-coalesced) 
===========                     =======  ======= 
Accelerate framework               640K        5 
Activity Tracing                   256K        1 
CG backing stores                 1440K        8 
CG image                           276K       34 
ColorSync                          224K       27 
CoreAnimation                     2964K      110 
CoreGraphics                        16K        3 
CoreUI image data                 1856K       29 
Foundation                          48K        2 
Kernel Alloc Once                    8K        1 
MALLOC                           216.9M       79 
MALLOC guard page                   48K       12 
MALLOC_NANO (reserved)           384.0M        1         reserved VM address space (unallocated)
ObjC additional data                15K        1 
SQLite page cache                  192K        3 
STACK GUARD                       56.0M        7 
Stack                             11.0M        7 
VM_ALLOCATE                       3168K       23 
__CTF                               756        1 
__DATA                            30.6M      515 
__DATA_CONST                      29.8M      336 
__DATA_DIRTY                      1653K      204 
__FONT_DATA                          4K        1 
__LINKEDIT                       646.1M       12 
__TEXT                           506.5M      532 
__UNICODE                          592K        1 
dyld private memory               1024K        1 
libnetwork                         128K        8 
mapped file                      267.6M       42 
shared memory                     2848K       23 
===========                     =======  ======= 
TOTAL                              2.1G     2029 
TOTAL, minus reserved VM space     1.7G     2029 



-----------
Full Report
-----------

{"app_name":"Xcodes","timestamp":"2022-10-19 14:36:27.00 +0800","app_version":"1.8.0","slice_uuid":"910f86fa-9767-33a5-a170-248c0c6493f2","build_version":"16","platform":1,"bundleID":"com.robotsandpencils.XcodesApp","share_with_app_devs":0,"is_first_party":0,"bug_type":"309","os_version":"macOS 12.6 (21G115)","incident_id":"C5078CBC-05D4-4088-94F3-199CADE8C0B4","name":"Xcodes"}
{
  "uptime" : 20000,
  "procLaunch" : "2022-10-19 13:38:24.6581 +0800",
  "procRole" : "Foreground",
  "version" : 2,
  "userID" : 501,
  "deployVersion" : 210,
  "modelCode" : "Macmini8,1",
  "procStartAbsTime" : 16778142875820,
  "coalitionID" : 5751,
  "osVersion" : {
    "train" : "macOS 12.6",
    "build" : "21G115",
    "releaseType" : "User"
  },
  "captureTime" : "2022-10-19 14:35:58.9474 +0800",
  "incident" : "C5078CBC-05D4-4088-94F3-199CADE8C0B4",
  "bug_type" : "309",
  "pid" : 26133,
  "procExitAbsTime" : 20232153254440,
  "cpuType" : "X86-64",
  "procName" : "Xcodes",
  "procPath" : "\/Applications\/Xcodes.app\/Contents\/MacOS\/Xcodes",
  "bundleInfo" : {"CFBundleShortVersionString":"1.8.0","CFBundleVersion":"16","CFBundleIdentifier":"com.robotsandpencils.XcodesApp"},
  "storeInfo" : {"deviceIdentifierForVendor":"2ECC75FE-9958-5C08-B92F-BEB6A1F2C190","thirdParty":true},
  "parentProc" : "launchd",
  "parentPid" : 1,
  "coalitionName" : "com.robotsandpencils.XcodesApp",
  "crashReporterKey" : "F24E6CF7-FE19-3EDC-73C9-79E00D87575A",
  "bridgeVersion" : {"build":"19P6067","train":"6.6"},
  "sip" : "enabled",
  "isCorpse" : 1,
  "exception" : {"codes":"0x0000000000000000, 0x0000000000000000","rawCodes":[0,0],"type":"EXC_CRASH","signal":"SIGABRT"},
  "asi" : {"libsystem_c.dylib":["abort() called"]},
  "extMods" : {"caller":{"thread_create":0,"thread_set_state":0,"task_for_pid":0},"system":{"thread_create":0,"thread_set_state":0,"task_for_pid":6},"targeted":{"thread_create":0,"thread_set_state":0,"task_for_pid":0},"warnings":0},
  "faultingThread" : 0,
  "threads" : [{"triggered":true,"id":487235,"threadState":{"r13":{"value":140704552679824,"symbolLocation":0,"symbol":"__stderrp"},"rax":{"value":0},"rflags":{"value":582},"cpu":{"value":0},"r14":{"value":6},"rsi":{"value":6},"r8":{"value":202908148568048},"cr2":{"value":140704552537768},"rdx":{"value":0},"r10":{"value":0},"r9":{"value":65535},"r15":{"value":22},"rbx":{"value":4581631488,"symbolLocation":0,"symbol":"_main_thread"},"trap":{"value":133},"err":{"value":33554760},"r11":{"value":582},"rip":{"value":140703454109710,"matchesCrashFrame":1},"rbp":{"value":140701966373456},"rsp":{"value":140701966373416},"r12":{"value":259},"rcx":{"value":140701966373416},"flavor":"x86_THREAD_STATE","rdi":{"value":259}},"queue":"com.apple.main-thread","frames":[{"imageOffset":32782,"symbol":"__pthread_kill","symbolLocation":10,"imageIndex":0},{"imageOffset":25087,"symbol":"pthread_kill","symbolLocation":263,"imageIndex":1},{"imageOffset":531748,"symbol":"abort","symbolLocation":123,"imageIndex":2},{"imageOffset":3124204,"symbol":"swift::fatalError(unsigned int, char const*, ...)","symbolLocation":252,"imageIndex":3},{"imageOffset":3125958,"symbol":"swift::runtime::AccessSet::insert(swift::runtime::Access*, void*, void*, swift::ExclusivityFlags)","symbolLocation":582,"imageIndex":3},{"imageOffset":3126050,"symbol":"swift_beginAccess","symbolLocation":66,"imageIndex":3},{"imageOffset":11428312,"symbol":"NSViewResponder.addContentPath(to:kind:in:observer:)","symbolLocation":66,"imageIndex":4},{"imageOffset":1717345,"symbol":"AccessibilityGeometryStorage.updatePath()","symbolLocation":814,"imageIndex":4},{"imageOffset":1716437,"symbol":"AccessibilityGeometryStorage.path.getter","symbolLocation":29,"imageIndex":4},{"imageOffset":10558472,"symbol":"AccessibilityNode.contentPath.getter","symbolLocation":194,"imageIndex":4},{"imageOffset":10574664,"symbol":"AccessibilityNode.contentFrameFromPath.getter","symbolLocation":36,"imageIndex":4},{"imageOffset":10575027,"symbol":"AccessibilityNode.contentFrame.getter","symbolLocation":141,"imageIndex":4},{"imageOffset":11023116,"symbol":"closure #1 in Sequence<>.sorted(with:)","symbolLocation":124,"imageIndex":4},{"imageOffset":3011594,"symbol":"specialized MutableCollection<>._insertionSort(within:sortedEnd:by:)","symbolLocation":128,"imageIndex":4},{"imageOffset":3010875,"symbol":"specialized UnsafeMutableBufferPointer._stableSortImpl(by:)","symbolLocation":1661,"imageIndex":4},{"imageOffset":3003387,"symbol":"specialized MutableCollection<>.sort(by:)","symbolLocation":90,"imageIndex":4},{"imageOffset":12173108,"symbol":"static Accessibility.queryChildren(element:options:)","symbolLocation":267,"imageIndex":4},{"imageOffset":9692451,"symbol":"static Accessibility.queryPlatformChildren(element:options:)","symbolLocation":93,"imageIndex":4},{"imageOffset":10453046,"symbol":"AccessibilityNode.accessibilityChildren()","symbolLocation":17,"imageIndex":4},{"imageOffset":10452944,"symbol":"@objc AccessibilityNode.accessibilityChildrenInNavigationOrder()","symbolLocation":31,"imageIndex":4},{"imageOffset":896574,"symbol":"-[NSAccessibilityAttributeAccessorInfo getAttributeValue:forObject:]","symbolLocation":58,"imageIndex":5},{"imageOffset":6599134,"symbol":"___NSAccessibilityEntryPointValueForAttribute_block_invoke.818","symbolLocation":1435,"imageIndex":5},{"imageOffset":6581468,"symbol":"NSAccessibilityPerformEntryPointObject","symbolLocation":16,"imageIndex":5},{"imageOffset":3235615,"symbol":"_NSAccessibilityEntryPointValueForAttribute","symbolLocation":168,"imageIndex":5},{"imageOffset":896005,"symbol":"NSAccessibilityChildren","symbolLocation":41,"imageIndex":5},{"imageOffset":902320,"symbol":"NSAccessibilityUnignoredChildren","symbolLocation":216,"imageIndex":5},{"imageOffset":9691900,"symbol":"static Accessibility.queryPlatformFilter(elements:options:)","symbolLocation":393,"imageIndex":4},{"imageOffset":11422285,"symbol":"NSHostingView.appKitAccessibilityChildren(options:)","symbolLocation":25,"imageIndex":4},{"imageOffset":11457228,"symbol":"NSHostingView.accessibilityChildren()","symbolLocation":14,"imageIndex":4},{"imageOffset":11457282,"symbol":"@objc NSHostingView.accessibilityChildren()","symbolLocation":24,"imageIndex":4},{"imageOffset":896574,"symbol":"-[NSAccessibilityAttributeAccessorInfo getAttributeValue:forObject:]","symbolLocation":58,"imageIndex":5},{"imageOffset":6599134,"symbol":"___NSAccessibilityEntryPointValueForAttribute_block_invoke.818","symbolLocation":1435,"imageIndex":5},{"imageOffset":6581468,"symbol":"NSAccessibilityPerformEntryPointObject","symbolLocation":16,"imageIndex":5},{"imageOffset":3235615,"symbol":"_NSAccessibilityEntryPointValueForAttribute","symbolLocation":168,"imageIndex":5},{"imageOffset":896005,"symbol":"NSAccessibilityChildren","symbolLocation":41,"imageIndex":5},{"imageOffset":902320,"symbol":"NSAccessibilityUnignoredChildren","symbolLocation":216,"imageIndex":5},{"imageOffset":901820,"symbol":"NSAccessibilityGetObjectForAttributeUsingLegacyAPI","symbolLocation":337,"imageIndex":5},{"imageOffset":900454,"symbol":"NSAccessibilityGetObjectValueForAttribute","symbolLocation":2718,"imageIndex":5},{"imageOffset":896574,"symbol":"-[NSAccessibilityAttributeAccessorInfo getAttributeValue:forObject:]","symbolLocation":58,"imageIndex":5},{"imageOffset":6599134,"symbol":"___NSAccessibilityEntryPointValueForAttribute_block_invoke.818","symbolLocation":1435,"imageIndex":5},{"imageOffset":6581468,"symbol":"NSAccessibilityPerformEntryPointObject","symbolLocation":16,"imageIndex":5},{"imageOffset":3235615,"symbol":"_NSAccessibilityEntryPointValueForAttribute","symbolLocation":168,"imageIndex":5},{"imageOffset":896005,"symbol":"NSAccessibilityChildren","symbolLocation":41,"imageIndex":5},{"imageOffset":902320,"symbol":"NSAccessibilityUnignoredChildren","symbolLocation":216,"imageIndex":5},{"imageOffset":8261041,"symbol":"-[NSTableViewCellMockElement accessibilityChildrenAttribute]","symbolLocation":115,"imageIndex":5},{"imageOffset":901820,"symbol":"NSAccessibilityGetObjectForAttributeUsingLegacyAPI","symbolLocation":337,"imageIndex":5},{"imageOffset":6600299,"symbol":"___NSAccessibilityEntryPointValueForAttribute_block_invoke.818","symbolLocation":2600,"imageIndex":5},{"imageOffset":6581468,"symbol":"NSAccessibilityPerformEntryPointObject","symbolLocation":16,"imageIndex":5},{"imageOffset":3235615,"symbol":"_NSAccessibilityEntryPointValueForAttribute","symbolLocation":168,"imageIndex":5},{"imageOffset":896005,"symbol":"NSAccessibilityChildren","symbolLocation":41,"imageIndex":5},{"imageOffset":2188456,"symbol":"-[NSObject(NSObjectAccessibilityAttributeAccessAdditions) accessibilityIndexOfChild:]","symbolLocation":14,"imageIndex":5},{"imageOffset":2188130,"symbol":"-[NSObject(NSAccessibilityUIElementSpecifier) _accessibilityUIElementSpecifierForChild:registerIfNeeded:]","symbolLocation":134,"imageIndex":5},{"imageOffset":1896766,"symbol":"-[NSObject(NSAccessibilityUIElementSpecifier) _accessibilityUIElementSpecifierRegisterIfNeeded:]","symbolLocation":146,"imageIndex":5},{"imageOffset":3239577,"symbol":"NSAccessibilityPostNotificationForObservedElementWithUserInfo","symbolLocation":440,"imageIndex":5},{"imageOffset":9695509,"symbol":"Accessibility.Notification.Info.post(name:)","symbolLocation":765,"imageIndex":4},{"imageOffset":1724105,"symbol":"AccessibilityGeometryStorage.contentPathDidChange()","symbolLocation":170,"imageIndex":4},{"imageOffset":1724234,"symbol":"AccessibilityGeometryStorage.PathObserver.contentPathDidChange()","symbolLocation":29,"imageIndex":4},{"imageOffset":687515,"symbol":"ContentPathObservers.notify()","symbolLocation":123,"imageIndex":4},{"imageOffset":8229326,"symbol":"specialized ViewResponderFilter.updateValue()","symbolLocation":504,"imageIndex":4},{"imageOffset":8478270,"symbol":"partial apply for specialized implicit closure #2 in implicit closure #1 in closure #1 in closure #1 in Attribute.init<A>(_:)","symbolLocation":32,"imageIndex":4},{"imageOffset":22359,"symbol":"AG::Graph::UpdateStack::update()","symbolLocation":559,"imageIndex":6},{"imageOffset":23895,"symbol":"AG::Graph::update_attribute(AG::data::ptr<AG::Node>, unsigned int)","symbolLocation":421,"imageIndex":6},{"imageOffset":48557,"symbol":"AG::Graph::value_ref(AG::AttributeID, AGSwiftMetadata const*, unsigned char&)","symbolLocation":155,"imageIndex":6},{"imageOffset":141919,"symbol":"AGGraphGetValue","symbolLocation":289,"imageIndex":6},{"imageOffset":2649393,"symbol":"ViewGraph.updateRequestedOutputs()","symbolLocation":239,"imageIndex":4},{"imageOffset":2648368,"symbol":"ViewGraph.updateOutputs()","symbolLocation":354,"imageIndex":4},{"imageOffset":11134582,"symbol":"closure #1 in ViewRendererHost.render(interval:updateDisplayList:)","symbolLocation":2065,"imageIndex":4},{"imageOffset":11049777,"symbol":"ViewRendererHost.render(interval:updateDisplayList:)","symbolLocation":374,"imageIndex":4},{"imageOffset":11441542,"symbol":"closure #1 in NSHostingView.layout()","symbolLocation":126,"imageIndex":4},{"imageOffset":11478852,"symbol":"partial apply for thunk for @callee_guaranteed (@guaranteed NSAnimationContext) -> ()","symbolLocation":17,"imageIndex":4},{"imageOffset":11430772,"symbol":"thunk for @escaping @callee_guaranteed (@guaranteed NSAnimationContext) -> ()","symbolLocation":40,"imageIndex":4},{"imageOffset":369067,"symbol":"+[NSAnimationContext runAnimationGroup:]","symbolLocation":55,"imageIndex":5},{"imageOffset":11441338,"symbol":"NSHostingView.layout()","symbolLocation":287,"imageIndex":4},{"imageOffset":11442362,"symbol":"@objc NSHostingView.layout()","symbolLocation":21,"imageIndex":4},{"imageOffset":613012,"symbol":"_NSViewLayout","symbolLocation":564,"imageIndex":5},{"imageOffset":611699,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":361,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":612033,"symbol":"-[NSView _layoutSubtreeWithOldSize:]","symbolLocation":695,"imageIndex":5},{"imageOffset":608901,"symbol":"-[NSView _layoutSubtreeIfNeededAndAllowTemporaryEngine:]","symbolLocation":1041,"imageIndex":5},{"imageOffset":607613,"symbol":"-[NSWindow(NSConstraintBasedLayout) _layoutViewTree]","symbolLocation":148,"imageIndex":5},{"imageOffset":1093261,"symbol":"-[NSWindow(NSConstraintBasedLayout) layoutIfNeeded]","symbolLocation":251,"imageIndex":5},{"imageOffset":1092812,"symbol":"__NSWindowGetDisplayCycleObserverForLayout_block_invoke","symbolLocation":430,"imageIndex":5},{"imageOffset":1089367,"symbol":"NSDisplayCycleObserverInvoke","symbolLocation":155,"imageIndex":5},{"imageOffset":1088228,"symbol":"NSDisplayCycleFlush","symbolLocation":921,"imageIndex":5},{"imageOffset":16318,"symbol":"CA::Transaction::run_commit_handlers(CATransactionPhase)","symbolLocation":98,"imageIndex":7},{"imageOffset":11484,"symbol":"CA::Transaction::commit()","symbolLocation":376,"imageIndex":7},{"imageOffset":1749457,"symbol":"__62+[CATransaction(NSCATransaction) NS_setFlushesWithDisplayLink]_block_invoke","symbolLocation":285,"imageIndex":5},{"imageOffset":9383772,"symbol":"___NSRunLoopObserverCreateWithHandler_block_invoke","symbolLocation":41,"imageIndex":5},{"imageOffset":521504,"symbol":"__CFRUNLOOP_IS_CALLING_OUT_TO_AN_OBSERVER_CALLBACK_FUNCTION__","symbolLocation":23,"imageIndex":8},{"imageOffset":521138,"symbol":"__CFRunLoopDoObservers","symbolLocation":543,"imageIndex":8},{"imageOffset":518212,"symbol":"__CFRunLoopRun","symbolLocation":840,"imageIndex":8},{"imageOffset":515644,"symbol":"CFRunLoopRunSpecific","symbolLocation":562,"imageIndex":8},{"imageOffset":189926,"symbol":"RunCurrentEventLoopInMode","symbolLocation":292,"imageIndex":9},{"imageOffset":188947,"symbol":"ReceiveNextEventCommon","symbolLocation":283,"imageIndex":9},{"imageOffset":188645,"symbol":"_BlockUntilNextEventMatchingListInModeWithFilter","symbolLocation":70,"imageIndex":9},{"imageOffset":257965,"symbol":"_DPSNextEvent","symbolLocation":927,"imageIndex":5},{"imageOffset":251498,"symbol":"-[NSApplication(NSEvent) _nextEventMatchingEventMask:untilDate:inMode:dequeue:]","symbolLocation":1394,"imageIndex":5},{"imageOffset":195865,"symbol":"-[NSApplication run]","symbolLocation":586,"imageIndex":5},{"imageOffset":15511,"symbol":"NSApplicationMain","symbolLocation":817,"imageIndex":5},{"imageOffset":508060,"symbol":"specialized runApp(_:)","symbolLocation":161,"imageIndex":4},{"imageOffset":11396132,"symbol":"runApp<A>(_:)","symbolLocation":164,"imageIndex":4},{"imageOffset":6122591,"symbol":"static App.main()","symbolLocation":63,"imageIndex":4},{"imageOffset":9713,"imageIndex":10},{"imageOffset":21806,"symbol":"start","symbolLocation":462,"imageIndex":11}]},{"id":487327,"name":"com.apple.NSEventThread","frames":[{"imageOffset":6522,"symbol":"mach_msg_trap","symbolLocation":10,"imageIndex":0},{"imageOffset":7400,"symbol":"mach_msg","symbolLocation":56,"imageIndex":0},{"imageOffset":525165,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":319,"imageIndex":8},{"imageOffset":518648,"symbol":"__CFRunLoopRun","symbolLocation":1276,"imageIndex":8},{"imageOffset":515644,"symbol":"CFRunLoopRunSpecific","symbolLocation":562,"imageIndex":8},{"imageOffset":1755598,"symbol":"_NSEventThread","symbolLocation":132,"imageIndex":5},{"imageOffset":25825,"symbol":"_pthread_start","symbolLocation":125,"imageIndex":1},{"imageOffset":8043,"symbol":"thread_start","symbolLocation":15,"imageIndex":1}]},{"id":609424,"name":"com.apple.NSURLConnectionLoader","frames":[{"imageOffset":6522,"symbol":"mach_msg_trap","symbolLocation":10,"imageIndex":0},{"imageOffset":7400,"symbol":"mach_msg","symbolLocation":56,"imageIndex":0},{"imageOffset":525165,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":319,"imageIndex":8},{"imageOffset":518648,"symbol":"__CFRunLoopRun","symbolLocation":1276,"imageIndex":8},{"imageOffset":515644,"symbol":"CFRunLoopRunSpecific","symbolLocation":562,"imageIndex":8},{"imageOffset":2398188,"imageIndex":12},{"imageOffset":362900,"symbol":"__NSThread__start__","symbolLocation":1009,"imageIndex":13},{"imageOffset":25825,"symbol":"_pthread_start","symbolLocation":125,"imageIndex":1},{"imageOffset":8043,"symbol":"thread_start","symbolLocation":15,"imageIndex":1}]},{"id":613437,"queue":"com.apple.root.default-qos","frames":[{"imageOffset":6522,"symbol":"mach_msg_trap","symbolLocation":10,"imageIndex":0},{"imageOffset":7400,"symbol":"mach_msg","symbolLocation":56,"imageIndex":0},{"imageOffset":525165,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":319,"imageIndex":8},{"imageOffset":518648,"symbol":"__CFRunLoopRun","symbolLocation":1276,"imageIndex":8},{"imageOffset":515644,"symbol":"CFRunLoopRunSpecific","symbolLocation":562,"imageIndex":8},{"imageOffset":967950,"symbol":"-[NSConcreteTask waitUntilExit]","symbolLocation":332,"imageIndex":13},{"imageOffset":540943,"imageIndex":10},{"imageOffset":543589,"imageIndex":10},{"imageOffset":17417,"imageIndex":10},{"imageOffset":8396,"symbol":"_dispatch_call_block_and_release","symbolLocation":12,"imageIndex":14},{"imageOffset":13079,"symbol":"_dispatch_client_callout","symbolLocation":8,"imageIndex":14},{"imageOffset":23036,"symbol":"_dispatch_queue_override_invoke","symbolLocation":787,"imageIndex":14},{"imageOffset":76482,"symbol":"_dispatch_root_queue_drain","symbolLocation":343,"imageIndex":14},{"imageOffset":78428,"symbol":"_dispatch_worker_thread2","symbolLocation":160,"imageIndex":14},{"imageOffset":12170,"symbol":"_pthread_wqthread","symbolLocation":256,"imageIndex":1},{"imageOffset":8023,"symbol":"start_wqthread","symbolLocation":15,"imageIndex":1}]},{"id":618707,"frames":[{"imageOffset":8008,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":1}]},{"id":618708,"frames":[{"imageOffset":8008,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":1}]},{"id":619353,"frames":[{"imageOffset":8008,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":1}]}],
  "usedImages" : [
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703454076928,
    "size" : 229376,
    "uuid" : "8cc28466-fd2f-3c80-9834-9525b7beac19",
    "path" : "\/usr\/lib\/system\/libsystem_kernel.dylib",
    "name" : "libsystem_kernel.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703454306304,
    "size" : 49152,
    "uuid" : "b5454e27-e8c7-3fdb-b77f-714f1e82e70b",
    "path" : "\/usr\/lib\/system\/libsystem_pthread.dylib",
    "name" : "libsystem_pthread.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703453061120,
    "size" : 561152,
    "uuid" : "e42e9d7a-03b4-340b-b61e-dcd45fd4acc0",
    "path" : "\/usr\/lib\/system\/libsystem_c.dylib",
    "name" : "libsystem_c.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703677362176,
    "size" : 4694016,
    "uuid" : "9b8f4225-6ea3-313c-b5b2-7b594e2d1ef1",
    "path" : "\/usr\/lib\/swift\/libswiftCore.dylib",
    "name" : "libswiftCore.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140707939651584,
    "CFBundleShortVersionString" : "3.5.2",
    "CFBundleIdentifier" : "com.apple.SwiftUI",
    "size" : 15335424,
    "uuid" : "c9ddd0f6-537b-305a-9175-8e6b4e748028",
    "path" : "\/System\/Library\/Frameworks\/SwiftUI.framework\/Versions\/A\/SwiftUI",
    "name" : "SwiftUI",
    "CFBundleVersion" : "3.5.2"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703499157504,
    "CFBundleShortVersionString" : "6.9",
    "CFBundleIdentifier" : "com.apple.AppKit",
    "size" : 15269888,
    "uuid" : "06015263-62ac-3b08-a298-dc835c18452a",
    "path" : "\/System\/Library\/Frameworks\/AppKit.framework\/Versions\/C\/AppKit",
    "name" : "AppKit",
    "CFBundleVersion" : "2113.60.148"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140707954987008,
    "CFBundleShortVersionString" : "3.2.1",
    "CFBundleIdentifier" : "com.apple.AttributeGraph",
    "size" : 225280,
    "uuid" : "06f5a511-e357-3dad-83c8-74bd8fc16b91",
    "path" : "\/System\/Library\/PrivateFrameworks\/AttributeGraph.framework\/Versions\/A\/AttributeGraph",
    "name" : "AttributeGraph",
    "CFBundleVersion" : "3.2.1"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703573295104,
    "CFBundleShortVersionString" : "1.11",
    "CFBundleIdentifier" : "com.apple.QuartzCore",
    "size" : 3223552,
    "uuid" : "fe25fa55-548b-3a42-84bb-31b16eace40e",
    "path" : "\/System\/Library\/Frameworks\/QuartzCore.framework\/Versions\/A\/QuartzCore",
    "name" : "QuartzCore",
    "CFBundleVersion" : "964.35"
  },
  {
    "source" : "P",
    "arch" : "x86_64h",
    "base" : 140703454621696,
    "CFBundleShortVersionString" : "6.9",
    "CFBundleIdentifier" : "com.apple.CoreFoundation",
    "size" : 5255168,
    "uuid" : "93c48919-68af-367e-9a67-db4159bc962c",
    "path" : "\/System\/Library\/Frameworks\/CoreFoundation.framework\/Versions\/A\/CoreFoundation",
    "name" : "CoreFoundation",
    "CFBundleVersion" : "1866"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703602466816,
    "CFBundleShortVersionString" : "2.1.1",
    "CFBundleIdentifier" : "com.apple.HIToolbox",
    "size" : 3096576,
    "uuid" : "06fdecd6-9f69-397b-b1e2-a8226c0ba7ed",
    "path" : "\/System\/Library\/Frameworks\/Carbon.framework\/Versions\/A\/Frameworks\/HIToolbox.framework\/Versions\/A\/HIToolbox",
    "name" : "HIToolbox"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4382396416,
    "CFBundleShortVersionString" : "1.8.0",
    "CFBundleIdentifier" : "com.robotsandpencils.XcodesApp",
    "size" : 1933312,
    "uuid" : "910f86fa-9767-33a5-a170-248c0c6493f2",
    "path" : "\/Applications\/Xcodes.app\/Contents\/MacOS\/Xcodes",
    "name" : "Xcodes",
    "CFBundleVersion" : "16"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4581105664,
    "size" : 442368,
    "uuid" : "71febccd-d9dc-3599-9971-2b3407c588a8",
    "path" : "\/usr\/lib\/dyld",
    "name" : "dyld"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703532605440,
    "CFBundleShortVersionString" : "1335.0.3",
    "CFBundleIdentifier" : "com.apple.CFNetwork",
    "size" : 4784128,
    "uuid" : "e9a42d7f-04b9-3d22-ace5-46a1c2ecace7",
    "path" : "\/System\/Library\/Frameworks\/CFNetwork.framework\/Versions\/A\/CFNetwork",
    "name" : "CFNetwork",
    "CFBundleVersion" : "1335.0.3"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703469809664,
    "CFBundleShortVersionString" : "6.9",
    "CFBundleIdentifier" : "com.apple.Foundation",
    "size" : 3919872,
    "uuid" : "e22e60bb-ab77-3120-862f-92fa74feffcf",
    "path" : "\/System\/Library\/Frameworks\/Foundation.framework\/Versions\/C\/Foundation",
    "name" : "Foundation",
    "CFBundleVersion" : "1866"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703452520448,
    "size" : 290816,
    "uuid" : "1a04b380-76e4-3e4b-b0fc-9837533d021d",
    "path" : "\/usr\/lib\/system\/libdispatch.dylib",
    "name" : "libdispatch.dylib"
  }
],
  "sharedCache" : {
  "base" : 140703451049984,
  "size" : 19331678208,
  "uuid" : "73669942-bd8a-3e40-951f-7fbe07b51cb8"
},
  "vmSummary" : "ReadOnly portion of Libraries: Total=1.1G resident=0K(0%) swapped_out_or_unallocated=1.1G(100%)\nWritable regions: Total=622.5M written=0K(0%) resident=0K(0%) swapped_out=0K(0%) unallocated=622.5M(100%)\n\n                                VIRTUAL   REGION \nREGION TYPE                        SIZE    COUNT (non-coalesced) \n===========                     =======  ======= \nAccelerate framework               640K        5 \nActivity Tracing                   256K        1 \nCG backing stores                 1440K        8 \nCG image                           276K       34 \nColorSync                          224K       27 \nCoreAnimation                     2964K      110 \nCoreGraphics                        16K        3 \nCoreUI image data                 1856K       29 \nFoundation                          48K        2 \nKernel Alloc Once                    8K        1 \nMALLOC                           216.9M       79 \nMALLOC guard page                   48K       12 \nMALLOC_NANO (reserved)           384.0M        1         reserved VM address space (unallocated)\nObjC additional data                15K        1 \nSQLite page cache                  192K        3 \nSTACK GUARD                       56.0M        7 \nStack                             11.0M        7 \nVM_ALLOCATE                       3168K       23 \n__CTF                               756        1 \n__DATA                            30.6M      515 \n__DATA_CONST                      29.8M      336 \n__DATA_DIRTY                      1653K      204 \n__FONT_DATA                          4K        1 \n__LINKEDIT                       646.1M       12 \n__TEXT                           506.5M      532 \n__UNICODE                          592K        1 \ndyld private memory               1024K        1 \nlibnetwork                         128K        8 \nmapped file                      267.6M       42 \nshared memory                     2848K       23 \n===========                     =======  ======= \nTOTAL                              2.1G     2029 \nTOTAL, minus reserved VM space     1.7G     2029 \n",
  "legacyInfo" : {
  "threadTriggered" : {
    "queue" : "com.apple.main-thread"
  }
},
  "trialInfo" : {
  "rollouts" : [
    {
      "rolloutId" : "60da5e84ab0ca017dace9abf",
      "factorPackIds" : {

      },
      "deploymentId" : 240000008
    },
    {
      "rolloutId" : "6112e14f37f5d11121dcd519",
      "factorPackIds" : {
        "SIRI_TEXT_TO_SPEECH" : "634710168e8be655c1316aaa"
      },
      "deploymentId" : 240000229
    }
  ],
  "experiments" : [

  ]
}
}

Model: Macmini8,1, BootROM 1731.140.2.0.0 (iBridge: 19.16.16067.0.0,0), 6 processors, 6-Core Intel Core i5, 3 GHz, 16 GB, SMC 
Graphics: Intel UHD Graphics 630, Intel UHD Graphics 630, Built-In
Display: DELL U2417H, 1920 x 1080 (1080p FHD - Full High Definition), Main, MirrorOff, Online
Display: DELL P2314H, 1920 x 1080 (1080p FHD - Full High Definition), MirrorOff, Online
Memory Module: BANK 0/ChannelA-DIMM0, 16 GB, DDR4, 2667 MHz, Micron, MTA16ATF2G64HZ-2G6E1
AirPort: spairport_wireless_card_type_wifi (0x14E4, 0x7BF), wl0: Jul 12 2021 19:26:30 version 9.30.464.0.32.5.76 FWID 01-45ccefcd
Bluetooth: Version (null), 0 services, 0 devices, 0 incoming serial ports
Network Service: Wi-Fi, AirPort, en1
Network Service: Ethernet, Ethernet, en0
Network Service: iPhone, Ethernet, en7
Network Service: iPhone 2, Ethernet, en8
USB Device: USB31Bus
USB Device: Keychron K2
USB Device: iPhone
USB Device: USB 2.0 BILLBOARD
USB Device: T2Bus
USB Device: Headset
USB Device: Apple T2 Controller
Thunderbolt Bus: Mac mini, Apple Inc., 47.5
Thunderbolt Bus: Mac mini, Apple Inc., 47.5

```
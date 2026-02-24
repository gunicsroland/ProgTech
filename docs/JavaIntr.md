# Java Overview

## Java Standard Library (JSL)

The **Java Standard Library** contains a large collection of built-in classes and interfaces that provide core functionality for Java programs.

- Includes packages such as:
  - `java.lang` (automatically imported, e.g. `Object`, `String`, `Math`)
  - `java.util` (collections, utilities)
  - `java.io` / `java.nio` (input/output)
  - `java.net` (networking)
  - `java.time` (date and time API)

---
  
## Java Virtual Machine (JVM)

The **Java Virtual Machine** is responsible for executing Java bytecode.

<body class=""><script>!function(){try{var d=document.documentElement,c=d.classList;c.remove('light','dark');var e=localStorage.getItem('theme');if('system'===e||(!e&&true)){var t='(prefers-color-scheme: dark)',m=window.matchMedia(t);if(m.media!==t||m.matches){d.style.colorScheme = 'dark';c.add('dark')}else{d.style.colorScheme = 'light';c.add('light')}}else if(e){c.add(e|| '')}if(e==='light'||e==='dark')d.style.colorScheme=e}catch(e){}}()</script><script nonce="">!function(){try{const t=localStorage.getItem("oai/apps/chatTheme/user-2vSN5Z4vMABuDZVBPp1ELK30");document.documentElement.dataset.chatTheme="string"==typeof t?JSON.parse(t):void 0}catch(e){}}();</script><span data-testid="blocking-initial-modals-done" class="hidden"></span><div class="fixed inset-x-0 top-0 z-50 mt-4 flex justify-center select-none not-focus-within:sr-only"><a data-skip-to-content="" class="interactive-bg-secondary behavior-btn interactive-label-secondary rounded-2xl px-4 py-2 text-base print:hidden" href="#main">Átugrás a tartalomra</a></div><div class="flex h-svh w-screen flex-col"><div class="relative z-0 flex min-h-0 w-full flex-1"><div class="relative flex min-h-0 w-full flex-1"><div class="@container/main relative flex min-w-0 flex-1 flex-col -translate-y-[calc(env(safe-area-inset-bottom,0px)/2)] pt-[calc(env(safe-area-inset-bottom,0px)/2)]"><div data-scroll-root="" class="@w-sm/main:[scrollbar-gutter:stable_both-edges] touch:[scrollbar-width:none] relative flex min-h-0 min-w-0 flex-1 flex-col [scrollbar-gutter:stable] not-print:overflow-x-clip not-print:overflow-y-auto scroll-pt-(--header-height) [--sticky-padding-top:var(--header-height)] has-data-[fixed-header=less-than-xl]:@w-xl/main:scroll-pt-0 has-data-[fixed-header=less-than-xl]:@w-xl/main:[--sticky-padding-top:0px] has-data-[fixed-header=less-than-xxl]:@w-2xl/main:scroll-pt-0 has-data-[fixed-header=less-than-xxl]:@w-2xl/main:[--sticky-padding-top:0px]" style="--sticky-padding-bottom: 104px;"><header id="page-header" data-fixed-header="less-than-xl" class="draggable no-draggable-children sticky top-0 p-2 touch:p-2.5 flex items-center justify-between z-20 h-header-height bg-token-main-surface-primary pointer-events-none select-none [view-transition-name:var(--vt-page-header)] *:pointer-events-auto transition-none motion-safe:transition-none data-[fixed-header=less-than-xxl]:@w-2xl/main:bg-transparent data-[fixed-header=less-than-xxl]:@w-2xl/main:shadow-none! data-[fixed-header=less-than-xl]:@w-xl/main:bg-transparent data-[fixed-header=less-than-xl]:@w-xl/main:shadow-none! [box-shadow:var(--sharp-edge-top-shadow)] @w-xl/main:bg-token-main-surface-primary @w-xl/main:[box-shadow:var(--sharp-edge-top-shadow)]!"><div class="pointer-events-none absolute start-0 flex flex-col items-center gap-2 lg:start-1/2 ltr:-translate-x-1/2 rtl:translate-x-1/2"><div class="hidden lg:block"><div class="inline-flex items-center gap-1 rounded-full text-sm font-medium pe-2 bg-[#F1F1FB] text-[#5D5BD0] hover:bg-[#E4E4F6] dark:bg-[#373669] dark:text-[#DCDBF6] dark:hover:bg-[#414071]"><button type="button" class="button-glimmer-cta relative flex items-center gap-1 rounded-full bg-transparent ps-2.5 whitespace-nowrap text-current focus:outline-none py-2 pe-0"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" aria-hidden="true" class="icon-sm"><use href="/cdn/assets/sprites-core-bfiuxdzr.svg#102c34" fill="currentColor"></use></svg>Előfizetés a Plusra</button><button type="button" aria-label="Frissítési emlékeztető elvetése" class="ms-0 flex h-4 w-4 items-center justify-center rounded-full text-[black] hover:bg-[#E4E4F6] dark:text-[white] dark:hover:bg-[#414071] transform transition-all duration-200 ease-out pointer-events-auto visible translate-x-0 opacity-100" tabindex="0"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" aria-hidden="true" color="text-token-text-primary"><use href="/cdn/assets/sprites-core-bfiuxdzr.svg#5ed5de" fill="currentColor"></use></svg></button></div></div></div><div class="pointer-events-none! flex flex-1 items-center *:pointer-events-auto"><button type="button" class="touch:h-10 touch:w-10 inline-flex h-9 w-9 items-center justify-center rounded-md focus:outline-hidden hover:text-token-text-primary rounded-md focus:ring-2 focus:ring-white focus:ring-inset active:opacity-50" data-testid="open-sidebar-button" aria-expanded="false" aria-controls="stage-popover-sidebar"><span class="sr-only">Oldalsáv megnyitása</span><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" aria-hidden="true" data-rtl-flip="" class="text-token-text-secondary icon-lg mx-2"><use href="/cdn/assets/sprites-core-bfiuxdzr.svg#38e54b" fill="currentColor"></use></svg></button><button aria-label="Modellválasztó, a jelenlegi modell: 5.2" type="button" id="radix-_r_id_" aria-haspopup="menu" aria-expanded="false" data-state="closed" data-testid="model-switcher-dropdown-button" class="group flex cursor-pointer justify-center items-center gap-1 rounded-lg min-h-9 touch:min-h-10 px-2.5 text-lg hover:bg-token-surface-hover focus-visible:bg-token-surface-hover font-normal whitespace-nowrap focus-visible:outline-none" style="view-transition-name: var(--vt-thread-model-switcher);"><div>ChatGPT</div><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" aria-hidden="true" class="icon-sm text-token-text-tertiary"><use href="/cdn/assets/sprites-core-bfiuxdzr.svg#ba3792" fill="currentColor"></use></svg></button><div class="block lg:hidden"><div class="inline-flex items-center gap-1 rounded-full text-sm font-medium pe-2 bg-[#F1F1FB] text-[#5D5BD0] hover:bg-[#E4E4F6] dark:bg-[#373669] dark:text-[#DCDBF6] dark:hover:bg-[#414071]"><button type="button" class="button-glimmer-cta relative flex items-center gap-1 rounded-full bg-transparent ps-2.5 whitespace-nowrap text-current focus:outline-none py-2 pe-0"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" aria-hidden="true" class="icon-sm"><use href="/cdn/assets/sprites-core-bfiuxdzr.svg#102c34" fill="currentColor"></use></svg>Előfizetés a Plusra</button><button type="button" aria-label="Frissítési emlékeztető elvetése" class="ms-0 flex h-4 w-4 items-center justify-center rounded-full text-[black] hover:bg-[#E4E4F6] dark:text-[white] dark:hover:bg-[#414071] transform transition-all duration-200 ease-out pointer-events-auto visible translate-x-0 opacity-100" tabindex="0"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" aria-hidden="true" color="text-token-text-primary"><use href="/cdn/assets/sprites-core-bfiuxdzr.svg#5ed5de" fill="currentColor"></use></svg></button></div></div></div><div class="flex items-center justify-center gap-3 overflow-x-hidden"><div class="shrink-0"></div><div class="flex items-center justify-end gap-2 overflow-x-hidden"><div class="flex items-center" id="conversation-header-actions"><span class="" data-state="closed"><button data-testid="share-chat-button" class="text-token-text-primary no-draggable hover:bg-token-surface-hover keyboard-focused:bg-token-surface-hover touch:h-10 touch:w-10 flex h-9 w-9 items-center justify-center rounded-lg focus:outline-none disabled:opacity-50 max-sm:hidden" style="view-transition-name: var(--vt_share_chat_compact_button);"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" aria-hidden="true" class="icon"><use href="/cdn/assets/sprites-core-bfiuxdzr.svg#630ca2" fill="currentColor"></use></svg></button></span><div class="flex items-center"><div class="relative overflow-hidden" type="button" id="radix-_r_hh_" aria-haspopup="menu" aria-expanded="false" data-state="closed"><button aria-label="Beszélgetésopciók megnyitása" data-testid="conversation-options-button" class="text-token-text-primary no-draggable hover:bg-token-surface-hover keyboard-focused:bg-token-surface-hover touch:h-10 touch:w-10 flex h-9 w-9 items-center justify-center rounded-lg focus:outline-none disabled:opacity-50"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" aria-hidden="true" class="icon"><use href="/cdn/assets/sprites-core-bfiuxdzr.svg#f6d0e2" fill="currentColor"></use></svg></button></div></div></div></div></div></header><main class="min-h-0 flex-1" id="main" z-index="-1"><div id="thread" class="group/thread flex flex-col min-h-full"><div role="presentation" class="composer-parent flex flex-1 flex-col focus-visible:outline-0"><div class="relative basis-auto flex-col -mb-(--composer-overlap-px) [--composer-overlap-px:28px] grow flex"><div aria-hidden="true" data-edge="true" class="pointer-events-none h-px w-px absolute top-0"></div><div class="flex flex-col text-sm pb-25"><article class="text-token-text-primary w-full focus:outline-none [--shadow-height:45px] has-data-writing-block:pointer-events-none has-data-writing-block:-mt-(--shadow-height) has-data-writing-block:pt-(--shadow-height) [&amp;:has([data-writing-block])&gt;*]:pointer-events-auto scroll-mt-(--header-height)" tabindex="-1" dir="auto" data-turn-id="922544df-4df4-4e3b-b438-8114d0c4ac30" data-testid="conversation-turn-1" data-scroll-anchor="false" data-turn="user"><h5 class="sr-only">Ezt mondtad:</h5><div class="text-base my-auto mx-auto pt-3 [--thread-content-margin:--spacing(4)] @w-sm/main:[--thread-content-margin:--spacing(6)] @w-lg/main:[--thread-content-margin:--spacing(16)] px-(--thread-content-margin)"><div tabindex="-1" class="[--thread-content-max-width:40rem] @w-lg/main:[--thread-content-max-width:48rem] mx-auto max-w-(--thread-content-max-width) flex-1 group/turn-messages focus-visible:outline-hidden relative flex w-full min-w-0 flex-col"><div class="flex max-w-full flex-col grow"><div data-message-author-role="user" data-message-id="922544df-4df4-4e3b-b438-8114d0c4ac30" dir="auto" class="min-h-8 text-message relative flex w-full flex-col items-end gap-2 text-start break-words whitespace-normal [.text-message+&amp;]:mt-1"><div class="flex w-full flex-col gap-1 empty:hidden items-end rtl:items-start"><div class="user-message-bubble-color corner-superellipse/1.1 relative rounded-[18px] px-4 py-1.5 data-[multiline]:py-3 max-w-[var(--user-chat-width,70%)]" data-multiline=""><div class="whitespace-pre-wrap"># Java

## Java Standard Library (JVS)

Contains all the clasees of the java.lang package, like <code class="rounded-sm bg-(--theme-user-msg-text)/10 dark:bg-(--theme-user-msg-text)/15 px-1 py-0.5 text-(--theme-user-msg-text) text-sm">Object</code> class etc.

## Java Virtual Machine (JVM)

The **Java Virtual Machine** is responsible for executing Java bytecode.

### Responsibilities
- Loads `.class` files (bytecode) into memory
- Executes bytecode using an interpreter and/or Just-In-Time (JIT) compiler
- Provides **platform independence** (“write once, run anywhere”)
- Manages:
  - Memory allocation and deallocation
  - Garbage collection
  - Multithreading and thread scheduling
  - Security checks and runtime optimizations

> The JVM is platform-specific, but Java bytecode is platform-independent.

---

## Java Runtime Environment (JRE)

The **Java Runtime Environment** provides everything needed to **run** a Java application (but not to develop one).

### Contains
- Java Virtual Machine (JVM)
- Java Standard Library (JSL)
- Supporting runtime files and libraries

### Purpose
- Allows users to execute Java programs
- Does **not** include development or compilation tools

## Java Development Kit (JDK)

The **Java Development Kit** provides everything needed to **develop, compile, debug, and run** Java applications.

### Contains
- Java Runtime Environment (JRE)
- Development tools
- Header files and documentation (depending on distribution)

---

### Development tools

1. **`javac`** – Compiles `.java` source files into `.class` bytecode  
2. **`java`** – Launches the JVM and runs Java applications  
3. **Java Standard Library source code** – Reference implementation of core APIs  
4. **Debugger (`jdb`)** – Helps inspect and debug running programs  
5. **Monitoring & profiling tools**
   - `jconsole`
   - `jvisualvm`
   - Flight Recorder / Mission Control (in some distributions)

---

# Example: Running a Simple Java Program

## Step 0: Install Java (On Linux):

```bash
sudo apt install openjdk-25
```

## 1. Create a Java Source File

Create a file named `HelloWorld.java`:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

## 2. Compile the Program

Compile the java file

```bash
javac HelloWorld.java
```

It generates HelloWorld.class

## 3. Run the Program

execute it with JVM:

```bash
hava HelloWorld
```

<h1 align="center"> uninit </h1>

<h3 align="center"><bold><i>deconstruct, reconstruct</i></bold></h3>

<p align="center">
  uninit is a developer group focused on applications by people for people, <br />
  dedicated to high-performance multiplatform applications and always-improving 
  extensibility and ux.
</p>

<h2 align="center">
  Projects
</h2>

<h3 > mewsic </h3>

mewsic is a project (development slow) centered around making your music-listening
experience on mobile and desktop as good and user-focused as possible.

<h3 > genesis </h3>

genesis (development active) is a recreation, modernization, and multiplatform version
of discord's old android app before it moved to react native.

<h3 > rootVM </h3>

rootvm (development halted) is an x86-64 asm-inspired virtual machine planned to be
built for speed, reliability, and portability. 

<h2 align="center">
  Libraries
</h2>

<h3> uninit.common </h3>

Langs: Kotlin

uninit.common (development planned, merge of mewsic and genesis common libraries) is a 
kotlin multiplatform (jvm/android, jvm/desktop, iOS, web(?)) library which holds common
application features and utility pieces.

<h3> uninit.common.compose </h3>

Langs: Kotlin

uninit.common.compose (development planned) is a kotlin compose multiplatform (jvm/android,
jvm/desktop, iOS, web(?)) library which makes some compose flows much easier via common 
utilities such as preference managers.

<h3> uninit.innertube </h3>

Langs: Kotlin

uninit.innertube (development slow) is a kmp library focusing on two things, first and
foremost is an api accessor for youtube's internal backend. secondly, this focuses
on an intuitive and easy-to-use developer facing api.

<h3> uninit.mewsic.muse </h3>

Langs: Kotlin

uninit.mewsic.muse (development slow) is a kmp library focusing on common definitions
and utilities for music-playing apps, such as a multiplatform composable audio/video
player (via libmpv/libvlc on desktop, exoplayer on mobile, and the native player on
ios) and more.

<h3> rootir </h3>

Langs: Rust

rootir (development pending standardization of rootir) is a library that contains an
in-code representation, and a rootIR parser/packager/builder. This library will primarily
be used by rootVM.

<h3> vmalloc </h3>

Langs: Rust

vmalloc (development planned) is a custom layer ontop of the rust memory allocator which
makes allocating memory regions and manually managing them much easier and more efficient,
something that would be neccesary if you were making a fast VM.

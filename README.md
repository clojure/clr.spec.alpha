# clr.spec.alpha

A port of [clojure/spec.alpha](https://github.com/clojure/spec.alpha) library to ClojureCLR.

From the parent's README:

> spec is a Clojure library to describe the structure of data and functions. Specs can be used to validate data, conform (destructure) data, explain invalid data, generate examples that conform to the specs, and automatically use generative testing to test functions.

>Clojure 1.9 (still in alpha releases) depends on this library and provides it to users of Clojure. Thus, the recommended way to use this library is to add a dependency on the latest version of Clojure 1.9, rather than including it directly. In some cases, this library may release more frequently than Clojure. In those cases, you can explictly include the latest version of this library with the dependency info below.

# Releases

Nuget reference:

    PM> Install-Package clojure.spec.alpha

Leiningen/Clojars reference:

   [org.clojure.clr/spec.alpha "0.1.94"]
   
## Notes on the ported code ##

We are working through a large number of updates that have been made to the original code.

## Usage



# Copyright and License #

> Copyright (c) Rich Hickey, and contributors, 2017. All rights reserved.  The use and distribution terms for this software are covered by the Eclipse Public License 1.0 (http://opensource.org/licenses/eclipse-1.0.php) which can be found in the file epl-v10.html at the root of this distribution. By using this software in any fashion, you are agreeing to be bound bythe terms of this license.  You must not remove this notice, or any other, from this software.

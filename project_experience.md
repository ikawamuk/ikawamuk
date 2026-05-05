# Project Experience
## Web server software refer to nginx
- Period:2026/4 ~ 2026/6
- Technologies:C++
- Description:
	- Summary:A collaborative project (team of 2) to develop a high-performance HTTP/1.1 web server using C++98 and event-driven I/O.
	- Objective and Approaches:
		- Designed and implemented a robust HTTP request parser using a state machine to handle fragmented or large payloads efficiently.
		- Utilized I/O multiplexing (epoll/kqueue) to manage multiple concurrent client connections without blocking.
		- Ensured strict RFC compliance for header validation and chunked transfer encoding.

## Reimplementing a C compiler
- Period:2026/1 ~
- Technologies:C
- Description:
	- Summary:Developing a self-hosting C compiler that targets x86-64 assembly, focusing on understanding language internals and code generation.
	- Objective and Approaches:
		- Implemented a recursive descent parser to construct Abstract Syntax Trees (AST) from C source code.
		- Managed stack frame allocation and local variable scoping for x86-64 Linux environments.
		- Developed a code generator that converts AST nodes into assembly instructions, supporting arithmetic, control flow, and system calls.

## inplementing Quine
- Period:2026/2
- Technologies:C
- Description:
	- Summary:A deep dive into the concept of self-replicating programs (Quines) to explore the limits of source code and execution.
	- Objective and Approaches:
		- Researched and implemented the mathematical logic of self-replication without using external file I/O.
		- Explored the use of ASCII character codes and formatting strings to allow a program to output its own source code exactly.

## 3D renderer using path tracing
- Period:2025/12 ~ 2026/3
- Technologies:C
- Description:
	- Summary:A collaborative engine (team of 2) for rendering 3D scenes using raytracing and light transport simulation.
	- Objective and Approaches:
		- Designed and implemented the core light transport system, including Phong reflection models and shadow calculation.
		- Developed geometric intersection algorithms for primitives like spheres, cylinders, and triangles using vector calculus.
		- Achieved realistic visual effects through ray-object interaction and material properties.

## Simple Shell Implementation
- Period:2025/8 ~ 2025/10
- Technologies:C
- Description:
	- Summary:A collaborative development of a Bash-compatible command-line interpreter to understand process management and signals.
	- Objective and Approaches:
		- Implemented process control logic using fork, execve, and waitpid.
		- Developed features for pipelines (|) and redirections (>, >>, <), managing file descriptors and inter-process communication.
		- Handled environment variables and built-in commands while maintaining robust signal handling (e.g., Ctrl-C, Ctrl-D).

## Reimplementing libc
- Period:2025/4
- Technologies:C
- Description:
	- Summary:A foundational project to reimplement standard C library functions to master memory manipulation and pointer arithmetic.
	- Objective and Approaches:
		- Rewrote essential functions from <string.h> and <stdlib.h> without using existing libraries.
		- Focused on manual memory management and edge-case handling for string utilities.


# プロジェクト経験

## Nginxを参考にしたWebサーバーソフトウェア
- 期間: 2026年4月 ～ 2026年6月
- 使用技術: C++
- 内容:
	- 概要: C++98とイベント駆動型I/Oを用いた、高性能なHTTP/1.1 Webサーバーを開発する共同プロジェクト（2名体制）。
	- 目的とアプローチ:
		- ステートマシンを用いて、断片化されたデータや大きなペイロードを効率的に処理する堅牢なHTTPリクエストパーサーを設計・実装。
		- I/O多重化（epoll/kqueue）を活用し、ブロッキングなしで複数のクライアント接続を同時に管理。
		- ヘッダーの検証やチャンク転送エンコーディングにおいて、厳密なRFC準拠を確保。

## Cコンパイラの再実装
- 期間: 2026年1月 ～
- 使用技術: C
- 内容:
	- 概要: x86-64アセンブリをターゲットとしたセルフホスト可能なCコンパイラを開発。言語の内部構造とコード生成の理解に重点を置く。
	- 目的とアプローチ:
		- 再帰下降構文解析器を実装し、Cソースコードから抽象構文木（AST）を構築。
		- x86-64 Linux環境におけるスタックフレームの割り当てとローカル変数のスコープを管理。
		- ASTノードを算術演算、制御フロー、システムコールをサポートするアセンブリ命令に変換するコード生成器を開発。

## クワイン（Quine）の実装
- 期間: 2026年2月
- 使用技術: C
- 内容:
	- 概要: ソースコードと実行の限界を探求するため、自己複製プログラム（クワイン）の概念を深く調査。
	- 目的とアプローチ:
		- 外部ファイルI/Oを使用しない自己複製の数学的ロジックを研究・実装。
		- ASCII文字コードとフォーマット文字列の活用により、プログラムが自身のソースコードを正確に出力できるように設計。

## パストレーシングを用いた3Dレンダラー
- 期間: 2025年12月 ～ 2026年3月
- 使用技術: C
- 内容:
	- 概要: レイトレーシングと光輸送シミュレーションを用いて3Dシーンをレンダリングするエンジンの共同開発（2名体制）。
	- 目的とアプローチ:
		- フォン反射モデルや影の計算を含む、光輸送システムの中心部を設計・実装。
		- ベクトル解析を用いて、球体、円柱、三角形などのプリミティブに対する幾何学的な交差判定アルゴリズムを開発。
		- レイと物体の相互作用および材質特性を通じて、リアルな視覚効果を実現。

## シンプルなシェル（Shell）の実装
- 期間: 2025年8月 ～ 2025年10月
- 使用技術: C
- 内容:
	- 概要: プロセス管理とシグナルを理解するため、Bash互換のコマンドラインインタプリタを共同開発。
	- 目的とアプローチ:
		- fork、execve、waitpidを使用してプロセス制御ロジックを実装。
		- パイプライン（|）やリダイレクト（>、>>、<）の機能を開発し、ファイルディスクリプタとプロセス間通信を管理。
		- 堅牢なシグナル処理（Ctrl-C、Ctrl-Dなど）を維持しつつ、環境変数やビルトインコマンドを処理。

## libcの再実装
- 期間: 2025年4月
- 使用技術: C
- 内容:
	- 概要: メモリ操作とポインタ演算を習得するため、標準Cライブラリ関数を再実装する基礎的なプロジェクト。
	- 目的とアプローチ:
		- 既存のライブラリを使用せず、string.hやstdlib.hの必須関数を自作。
		- 文字列ユーティリティなどの関数において、手動メモリ管理とエッジケースの処理に注力。
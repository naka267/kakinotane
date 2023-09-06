<?php

// メッセージを保存するファイルのパス設定
define( 'FILENAME', './message.txt');
 
// タイムゾーン設定
date_default_timezone_set('Asia/Tokyo');

// 変数の初期化
$current_date = null;
$data = null;
$file_handle = null;
$split_data = null;
$message = array();
$message_array = array();
$success_message = null;
$error_message = array();
$clean = array();


if( !empty($_POST['btn_submit']) ) {
	
	// 表示名の入力チェック
	if( empty($_POST['view_name']) ) {
		$error_message[] = '表示名を入力してください。';
	} else {
		$clean['view_name'] = htmlspecialchars( $_POST['view_name'], ENT_QUOTES, 'UTF-8');
        $clean['view_name'] = preg_replace( '/\\r\\n|\\n|\\r/', '', $clean['view_name']);
	}
	
	// メッセージの入力チェック
	if( empty($_POST['message']) ) {
		$error_message[] = 'ひと言メッセージを入力してください。';
	} else {
		$clean['message'] = htmlspecialchars( $_POST['message'], ENT_QUOTES, 'UTF-8');
		$clean['message'] = preg_replace( '/\\r\\n|\\n|\\r/', '<br>', $clean['message']);
	}

	if( empty($error_message) ) {

		if( $file_handle = fopen( FILENAME, "a") ) {
	
		    // 書き込み日時を取得
			$current_date = date("Y-m-d H:i:s");
		
			// 書き込むデータを作成
			$data = "'".$clean['view_name']."','".$clean['message']."','".$current_date."'\n";
		
			// 書き込み
			fwrite( $file_handle, $data);
		
			// ファイルを閉じる
			fclose( $file_handle);

			$success_message = 'メッセージを書き込みました。';
		}
	}
}

if( $file_handle = fopen( FILENAME,'r') ) {
    while( $data = fgets($file_handle) ){

		$split_data = preg_split( '/\'/', $data);

		$message = array(
			'view_name' => $split_data[1],
			'message' => $split_data[3],
			'post_date' => $split_data[5]
		);
		array_unshift( $message_array, $message);
	}
    
    // ファイルを閉じる
    fclose( $file_handle);
}

?>

<!DOCTYPE html>
    <head>
      <html lang="ja">
      <meta charset="UTF=8"> 
     <title>Charm of JAPAN</title>
     <meta name="柿の種" content="">
           <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Hina+Mincho&family=Sawarabi+Mincho&display=swap" rel="stylesheet">
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Klee+One&display=swap" rel="stylesheet">
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2? family=Zen+Old+Mincho:wght@500&display=swap" rel="stylesheet">


        <link rel="shortcut icon" href="/favicon.ico">
<link rel="icon" type="image/vnd.microsoft.icon" href="/favicon.ico">
        

        </head>
      <body>
  <h1 id =title class="title">
 <br> <u>柿の種</u><br>　</h1>  
        <br><hr>
<head>
   <p><h1 id=mm>サイト内リンク</h1></p>
  <a href=#tt><h2 class=io><u>掲示板</u></h2>
    <a href=#ii><h2 class=io><u>リンク集</u></h2><a>
  <div class=hh>
  
    <p><h1 id=tt>掲示板</h1></p>
    </div>
  <?php if( !empty($success_message) ): ?>
  <hr>

<?php if( !empty($success_message) ): ?>
    <p class="success_message">
      <?php echo $success_message; ?></p> 
<?php endif; ?>
<?php if( !empty($error_message) ): ?>
    <ul class="error_message">
		<?php foreach( $error_message as $value ): ?>
            <li>
              <?php echo $value; ?></li>
		<?php endforeach; ?>
    </ul>
<?php endif; ?>
<form method="post">
	<div>
  <h1 id=keijibann><u></u></h1>
<form method="post">
	<div>
		<label for="view_name">ニックネーム</label>
		<input id="view_name" type="text" name="view_name" value="">
	</div>
	<div>
		<label for="message">メッセージ</label>
		<textarea id="message" name="message"></textarea>
	</div>
	<input type="submit" name="btn_submit" value="投稿">
</form>
    
  
  </div>
  <section>
<?php if( !empty($message_array) ){ ?>
<?php foreach( $message_array as $value ){ ?>
<article>
    <div class="info">
        <h2><?php echo $value['view_name']; ?></h2>
        <time><?php echo date('Y年m月d日 H:i', strtotime($value['post_date'])); ?></time>
    </div>
    <p><?php echo $value['message']; ?></p>
</article>
<?php } ?>
<?php } ?>
</section>
   <a href=#mm><h3 style="text-align: right" class=al><u><br>サイトトップへ</u></h3>
    <p><h1 class="oo" id="ii">リンク集</h1>  
 
   <a  href="https://sites.google.com/edu.nishiyamato.ed.jp/kensaku"><h2 class="io">  <u>NYGsites</u></h2></a>
  <a  href="https://sites.google.com/edu.nishiyamato.ed.jp/game"><h2 class="io">  <u>NYGgames</u></h2></a>
  <a href=#mm><h3 style="text-align: right" class=al><u><br>サイトトップへ</u></h3>
        <footer p style="text-align:center;margin-top: 2em;margin-bottom: 1em;"class="copy"><small>&copy;N & N TEAM 2023       </small></footer>
  
  

    

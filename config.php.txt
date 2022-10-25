<?php
/**
 * PanDownload 网页复刻版，PHP 语言版配置文件
 * ！！！请勿修改本文件，如果手动修改后再在后台设置，可能导致config.php文件被清空！！！
 *
 * @author Yuan_Tuo <yuantuo666@gmail.com>
 * @link https://imwcr.cn/
 * @link https://space.bilibili.com/88197958
 */
const programVersion = '2.2.4.1';
if (!defined('init')) {
	http_response_code(403); header('Content-Type: text/plain; charset=utf-8'); header('Refresh: 3;url=./');
	die("HTTP 403 禁止访问！\r\n此文件是 PanDownload 网页复刻版 PHP 语言版项目版本 " . programVersion . " 的配置文件！\r\n禁止直接访问！");
}
if (!function_exists('curl_init')) {
	http_response_code(503);
	header('Content-Type: text/plain; charset=utf-8');
	die("HTTP 503 服务不可用！\r\n您未安装或未启用 Curl 扩展，此程序无法运行！");
}

const Sitename = 'Pandownload 复刻版';

const BDUSS = 'pxVkZtfmpJRlYwT3FUb21odFhBTXJjaXAyYkJ1dlNifjhkZWpNSUR5SVJRSDVqRVFBQUFBJCQAAAAAAAAAAAEAAADtdBecAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABGzVmMRs1ZjN3';
const STOKEN = 'f1da2495a64910f237252a53ed0b3dfea1cbe5039a755c5b01b95164334f5605';
const SVIP_BDUSS = 'RGR0MzRkRnd2l5T2o0MUdqTmZkSjNZN0xYc2laQVJOYnJjSm85VW9hM2RQMzVqRVFBQUFBJCQAAAAAAAAAAAEAAABUPgE-3sjPrAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAN2yVmPdslZjSF';
const SVIP_STOKEN = 'c67474aa932ef66779a041ed09ecad46c449ac8b0aea90e1044588bc1835eba1';

const IsCheckPassword = false;
const Password = '';
const Footer = <<<'FoOtEr_Made_By_YuanTuo'

FoOtEr_Made_By_YuanTuo;
const APP_ID = '250528';
const DEBUG = false;

const USING_DB = false;
const DbConfig = array("servername" => "mysql.sqlpub.com:3306", "username" => "adminkod", "DBPassword" => "f88211b1872f7b82", "dbname" => "kodjiotest", "dbtable" => "bdwp");

const ADMIN_PASSWORD = 'aini1314';
const DownloadTimes = 99;
const DownloadLinkAvailableTime = 8;
const IsConfirmDownload = false;
const SVIPSwitchMod = 0;

const WECHAT_MOD = true;

const DefaultLanguage = 'en';
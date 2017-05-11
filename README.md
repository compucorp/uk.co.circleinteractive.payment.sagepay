/* 
 * Sagepay Extension for CiviCRM - Circle Interactive 2012-2014
 * Author: andyw@circle
 *
 * Distributed under the GNU General Public License, version 2
 * https://www.gnu.org/licenses/gpl-2.0.html 
 */

 
This branch implements the following : 

1- When a  CiviCRM form is submitted and you get redirected to Sagepay page, A transaction with positive amount should credit Income Account and debit Accounts Receivable.
2- When completing the payment in Sagepay and get redirected to CiviCRM, A transaction with positive amount should credit Accounts Receivable and debit payment processor financial account.
3- When a payment is canceled in Sagepay and the user get redirected to CiviCRM or manually canceling the pending contribution, A transaction with negative amount should credit Income Account and debit Accounts Receivable.

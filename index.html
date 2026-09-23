<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
  <title>PureFlow Water Station POS</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,500;14..32,600;14..32,700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    :root {
      --primary: #0EA5E9;
      --primary-dark: #0284C7;
      --accent: #14B8A6;
      --bg: #F8FAFC;
      --text: #0F172A;
      --text-light: #475569;
      --card-bg: #FFFFFF;
      --shadow-sm: 0 1px 3px rgba(0,0,0,0.06), 0 1px 2px rgba(0,0,0,0.04);
      --shadow-md: 0 4px 6px -1px rgba(0,0,0,0.07), 0 2px 4px -2px rgba(0,0,0,0.05);
      --shadow-lg: 0 10px 15px -3px rgba(0,0,0,0.08), 0 4px 6px -4px rgba(0,0,0,0.02);
      --radius: 12px;
      --radius-sm: 8px;
      --transition: all 0.2s ease;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.5;
      -webkit-font-smoothing: antialiased;
    }

    button { cursor: pointer; font-family: inherit; border: none; background: none; }
    input, select { font-family: inherit; font-size: 0.95rem; }

    .hidden { display: none !important; }
    .flex { display: flex; }
    .items-center { align-items: center; }
    .justify-between { justify-content: space-between; }
    .gap-2 { gap: 0.5rem; }
    .gap-3 { gap: 0.75rem; }
    .text-sm { font-size: 0.875rem; }
    .text-xs { font-size: 0.75rem; }
    .text-light { color: var(--text-light); }
    .mt-2 { margin-top: 0.5rem; }
    .w-full { width: 100%; }
    .text-center { text-align: center; }

    /* Login */
    .login-container {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(145deg, #0EA5E9 0%, #0284C7 100%);
      padding: 1.5rem;
    }

    .login-card {
      background: var(--card-bg);
      border-radius: var(--radius);
      box-shadow: var(--shadow-lg);
      width: 100%;
      max-width: 420px;
      padding: 2rem 2rem 2.5rem;
      animation: fadeInUp 0.4s ease;
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(12px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .login-logo {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-bottom: 2rem;
    }

    .logo-icon {
      width: 64px;
      height: 64px;
      background: linear-gradient(135deg, #0EA5E9, #14B8A6);
      border-radius: 18px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 1.8rem;
      margin-bottom: 0.75rem;
      box-shadow: 0 8px 16px rgba(14,165,233,0.3);
    }

    .login-logo h1 { font-size: 1.5rem; font-weight: 700; color: var(--text); }
    .login-logo p { color: var(--text-light); font-size: 0.9rem; }

    .input-group { margin-bottom: 1.25rem; }
    .input-group label {
      display: block;
      font-size: 0.85rem;
      font-weight: 500;
      color: var(--text);
      margin-bottom: 0.35rem;
    }

    .input-wrapper { position: relative; }

    .input-wrapper input {
      width: 100%;
      padding: 0.75rem 2.5rem 0.75rem 1rem;
      border: 1.5px solid #E2E8F0;
      border-radius: var(--radius-sm);
      font-size: 0.95rem;
      transition: var(--transition);
      background: #F8FAFC;
    }

    .input-wrapper input:focus {
      outline: none;
      border-color: var(--primary);
      background: white;
      box-shadow: 0 0 0 3px rgba(14,165,233,0.15);
    }

    .input-wrapper i {
      position: absolute;
      right: 12px;
      top: 50%;
      transform: translateY(-50%);
      color: #94A3B8;
      cursor: pointer;
      font-size: 1rem;
    }

    .login-options {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin: 1.25rem 0 1.75rem;
      font-size: 0.85rem;
      color: var(--text-light);
    }

    .login-options label { display: flex; align-items: center; gap: 0.4rem; cursor: pointer; }

    .login-btn {
      width: 100%;
      padding: 0.85rem;
      background: linear-gradient(135deg, #0EA5E9, #0284C7);
      color: white;
      font-weight: 600;
      font-size: 1rem;
      border-radius: var(--radius-sm);
      transition: var(--transition);
      box-shadow: 0 4px 12px rgba(14,165,233,0.3);
    }

    .login-btn:hover {
      background: linear-gradient(135deg, #0284C7, #0369A1);
      box-shadow: 0 6px 16px rgba(14,165,233,0.4);
      transform: translateY(-1px);
    }

    .demo-hint {
      margin-top: 1.5rem;
      padding: 0.75rem 1rem;
      background: #F1F5F9;
      border-radius: var(--radius-sm);
      font-size: 0.8rem;
      color: var(--text-light);
      text-align: center;
    }

    .demo-hint strong { color: var(--text); }

    /* App layout */
    .app-container { display: flex; min-height: 100vh; }

    .sidebar {
      width: 260px;
      background: white;
      border-right: 1px solid #E9EEF5;
      display: flex;
      flex-direction: column;
      position: fixed;
      top: 0; bottom: 0; left: 0;
      z-index: 40;
      transition: transform 0.25s ease;
      box-shadow: 1px 0 8px rgba(0,0,0,0.02);
    }

    .sidebar-header {
      padding: 1.5rem 1.25rem 1rem;
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }

    .sidebar-header .logo-icon {
      width: 40px;
      height: 40px;
      font-size: 1.2rem;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(14,165,233,0.25);
    }

    .sidebar-header h2 { font-size: 1.1rem; font-weight: 700; color: var(--text); line-height: 1.2; }
    .sidebar-header span { font-size: 0.7rem; color: var(--text-light); font-weight: 400; }

    .nav-menu { flex: 1; padding: 0.5rem 0.75rem; overflow-y: auto; }

    .nav-item {
      display: flex;
      align-items: center;
      gap: 0.85rem;
      padding: 0.75rem 1rem;
      border-radius: var(--radius-sm);
      color: var(--text-light);
      font-weight: 500;
      font-size: 0.9rem;
      transition: var(--transition);
      margin-bottom: 0.15rem;
      cursor: pointer;
    }

    .nav-item i { width: 20px; text-align: center; font-size: 1rem; }
    .nav-item:hover { background: #F1F5F9; color: var(--text); }

    .nav-item.active {
      background: linear-gradient(135deg, rgba(14,165,233,0.1), rgba(20,184,166,0.1));
      color: var(--primary-dark);
      font-weight: 600;
    }

    .nav-item.active i { color: var(--primary); }

    .sidebar-footer { padding: 1rem 1.25rem; border-top: 1px solid #E9EEF5; }

    .user-info { display: flex; align-items: center; gap: 0.75rem; margin-bottom: 0.75rem; }

    .user-avatar {
      width: 38px;
      height: 38px;
      background: linear-gradient(135deg, #0EA5E9, #14B8A6);
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: 600;
      font-size: 0.9rem;
      flex-shrink: 0;
    }

    .user-details { flex: 1; min-width: 0; }
    .user-details .name { font-weight: 600; font-size: 0.9rem; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
    .user-details .role { font-size: 0.7rem; color: var(--text-light); text-transform: uppercase; letter-spacing: 0.3px; }

    .logout-btn {
      width: 100%;
      padding: 0.6rem;
      border-radius: var(--radius-sm);
      background: #FEF2F2;
      color: #DC2626;
      font-weight: 500;
      font-size: 0.85rem;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 0.5rem;
      transition: var(--transition);
    }

    .logout-btn:hover { background: #FEE2E2; }

    .main-content {
      flex: 1;
      margin-left: 260px;
      padding: 1.5rem 2rem 2.5rem;
      background: var(--bg);
      min-height: 100vh;
    }

    .menu-toggle {
      display: none;
      position: fixed;
      bottom: 1.5rem;
      right: 1.5rem;
      width: 52px;
      height: 52px;
      border-radius: 50%;
      background: var(--primary);
      color: white;
      font-size: 1.3rem;
      box-shadow: 0 4px 14px rgba(14,165,233,0.45);
      z-index: 50;
      align-items: center;
      justify-content: center;
    }

    /* Page header */
    .page-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 1.75rem;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .page-header h1 { font-size: 1.5rem; font-weight: 700; color: var(--text); }
    .page-header .subtitle { font-size: 0.85rem; color: var(--text-light); margin-top: 0.15rem; }

    /* Cards */
    .card {
      background: var(--card-bg);
      border-radius: var(--radius);
      box-shadow: var(--shadow-sm);
      padding: 1.25rem 1.5rem;
      border: 1px solid #EFF3F8;
    }

    .stat-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
      gap: 1rem;
      margin-bottom: 1.75rem;
    }

    .stat-card {
      background: white;
      border-radius: var(--radius);
      padding: 1.25rem 1.25rem 1rem;
      box-shadow: var(--shadow-sm);
      border: 1px solid #EFF3F8;
      transition: var(--transition);
    }

    .stat-card:hover { box-shadow: var(--shadow-md); transform: translateY(-2px); }

    .stat-card .label {
      font-size: 0.75rem;
      color: var(--text-light);
      text-transform: uppercase;
      letter-spacing: 0.4px;
      font-weight: 600;
      margin-bottom: 0.35rem;
    }

    .stat-card .value { font-size: 1.5rem; font-weight: 700; color: var(--text); line-height: 1.2; }
    .stat-card .sub { font-size: 0.75rem; color: var(--text-light); margin-top: 0.2rem; }

    .stat-card .icon {
      float: right;
      width: 36px;
      height: 36px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1rem;
      background: rgba(14,165,233,0.1);
      color: var(--primary);
    }

    /* Charts */
    .charts-grid {
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 1.25rem;
      margin-bottom: 1.75rem;
    }

    .chart-card {
      background: white;
      border-radius: var(--radius);
      padding: 1.25rem 1.5rem 1.5rem;
      box-shadow: var(--shadow-sm);
      border: 1px solid #EFF3F8;
    }

    .chart-card h3 { font-size: 0.95rem; font-weight: 600; margin-bottom: 1rem; color: var(--text); }
    .chart-container { position: relative; height: 200px; }

    /* Stock list */
    .stock-list { margin-top: 0.5rem; }

    .stock-item {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0.55rem 0;
      border-bottom: 1px solid #F1F5F9;
    }

    .stock-item:last-child { border-bottom: none; }
    .stock-item .size { font-weight: 500; font-size: 0.9rem; display: flex; align-items: center; gap: 0.4rem; }
    .stock-item .qty { font-weight: 600; font-size: 0.9rem; }
    .stock-item .qty.low { color: #DC2626; }

    .badge {
      display: inline-block;
      padding: 0.2rem 0.6rem;
      border-radius: 20px;
      font-size: 0.7rem;
      font-weight: 600;
      letter-spacing: 0.2px;
    }

    .badge-success { background: #DCFCE7; color: #166534; }
    .badge-warning { background: #FEF3C7; color: #92400E; }
    .badge-danger { background: #FEE2E2; color: #991B1B; }
    .badge-info { background: #DBEAFE; color: #1E40AF; }

    /* POS */
    .pos-grid {
      display: grid;
      grid-template-columns: 1fr 380px;
      gap: 1.5rem;
      align-items: start;
    }

    .pos-type-selector { display: flex; gap: 0.75rem; margin-bottom: 1.5rem; flex-wrap: wrap; }

    .pos-type-btn {
      flex: 1;
      padding: 0.85rem 1rem;
      border-radius: var(--radius-sm);
      background: white;
      border: 2px solid #E2E8F0;
      font-weight: 600;
      font-size: 0.9rem;
      color: var(--text-light);
      transition: var(--transition);
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 0.5rem;
      min-width: 180px;
    }

    .pos-type-btn.active {
      border-color: var(--primary);
      background: rgba(14,165,233,0.05);
      color: var(--primary-dark);
    }

    .pos-type-btn i { font-size: 1.1rem; }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
      gap: 1rem;
    }

    .product-card {
      background: white;
      border-radius: var(--radius-sm);
      padding: 1rem;
      box-shadow: var(--shadow-sm);
      border: 1px solid #EFF3F8;
      text-align: center;
      transition: var(--transition);
      cursor: pointer;
      position: relative;
    }

    .product-card:hover { box-shadow: var(--shadow-md); transform: translateY(-2px); border-color: var(--primary); }

    .product-card .icon-bottle { font-size: 2rem; color: var(--primary); margin-bottom: 0.3rem; }
    .product-card .name { font-weight: 600; font-size: 0.9rem; }
    .product-card .price { font-weight: 700; color: var(--primary-dark); font-size: 1rem; margin: 0.2rem 0; }
    .product-card .stock { font-size: 0.75rem; color: var(--text-light); }
    .product-card .stock.low { color: #DC2626; font-weight: 600; }

    .product-card .add-btn {
      margin-top: 0.6rem;
      width: 100%;
      padding: 0.45rem;
      background: var(--primary);
      color: white;
      border-radius: 6px;
      font-size: 0.8rem;
      font-weight: 600;
      transition: var(--transition);
    }

    .product-card .add-btn:hover { background: var(--primary-dark); }
    .product-card .add-btn:disabled { background: #CBD5E1; cursor: not-allowed; }

    /* Refill form */
    .refill-form {
      background: white;
      border-radius: var(--radius);
      padding: 1.5rem;
      box-shadow: var(--shadow-sm);
      border: 1px solid #EFF3F8;
    }

    .refill-form .form-row { margin-bottom: 1.25rem; }
    .refill-form label { display: block; font-size: 0.85rem; font-weight: 500; margin-bottom: 0.35rem; }

    .refill-form select,
    .refill-form input {
      width: 100%;
      padding: 0.7rem 1rem;
      border: 1.5px solid #E2E8F0;
      border-radius: var(--radius-sm);
      font-size: 0.95rem;
      transition: var(--transition);
      background: #F8FAFC;
    }

    .refill-form select:focus,
    .refill-form input:focus {
      outline: none;
      border-color: var(--primary);
      background: white;
      box-shadow: 0 0 0 3px rgba(14,165,233,0.12);
    }

    .refill-total {
      background: #F0F9FF;
      border-radius: var(--radius-sm);
      padding: 1rem;
      margin: 1.25rem 0;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .refill-total .label { font-weight: 500; color: var(--text-light); }
    .refill-total .amount { font-size: 1.5rem; font-weight: 700; color: var(--primary-dark); }

    /* Cart */
    .cart-panel {
      background: white;
      border-radius: var(--radius);
      box-shadow: var(--shadow-md);
      border: 1px solid #EFF3F8;
      position: sticky;
      top: 1.5rem;
    }

    .cart-header {
      padding: 1.25rem 1.5rem;
      border-bottom: 1px solid #EFF3F8;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .cart-header h3 { font-size: 1rem; font-weight: 600; }
    .cart-items { padding: 0.5rem 1.25rem; max-height: 340px; overflow-y: auto; }

    .cart-item {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      padding: 0.75rem 0;
      border-bottom: 1px solid #F1F5F9;
    }

    .cart-item:last-child { border-bottom: none; }
    .cart-item .info { flex: 1; min-width: 0; }
    .cart-item .info .name { font-weight: 500; font-size: 0.9rem; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
    .cart-item .info .price { font-size: 0.8rem; color: var(--text-light); }

    .cart-item .qty-controls { display: flex; align-items: center; gap: 0.3rem; }

    .qty-btn {
      width: 26px;
      height: 26px;
      border-radius: 6px;
      background: #F1F5F9;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 600;
      font-size: 0.8rem;
      color: var(--text);
      transition: var(--transition);
    }

    .qty-btn:hover { background: #E2E8F0; }

    .cart-item .subtotal { font-weight: 600; font-size: 0.9rem; min-width: 60px; text-align: right; }
    .cart-item .remove { color: #94A3B8; font-size: 0.9rem; padding: 0.2rem; transition: var(--transition); }
    .cart-item .remove:hover { color: #DC2626; }

    .cart-footer {
      padding: 1.25rem 1.5rem;
      border-top: 1px solid #EFF3F8;
      background: #FAFCFE;
      border-radius: 0 0 var(--radius) var(--radius);
    }

    .cart-totals { margin-bottom: 1rem; }
    .cart-totals .row { display: flex; justify-content: space-between; margin-bottom: 0.4rem; font-size: 0.9rem; }
    .cart-totals .row.total { font-weight: 700; font-size: 1.1rem; color: var(--text); margin-top: 0.5rem; padding-top: 0.5rem; border-top: 1px solid #E2E8F0; }

    .payment-selector { display: flex; gap: 0.5rem; margin-bottom: 1rem; }

    .payment-btn {
      flex: 1;
      padding: 0.55rem;
      border-radius: var(--radius-sm);
      border: 1.5px solid #E2E8F0;
      background: white;
      font-size: 0.8rem;
      font-weight: 500;
      color: var(--text-light);
      transition: var(--transition);
    }

    .payment-btn.active {
      border-color: var(--primary);
      background: rgba(14,165,233,0.05);
      color: var(--primary-dark);
      font-weight: 600;
    }

    .complete-sale-btn {
      width: 100%;
      padding: 0.85rem;
      background: linear-gradient(135deg, #0EA5E9, #0284C7);
      color: white;
      font-weight: 600;
      font-size: 0.95rem;
      border-radius: var(--radius-sm);
      transition: var(--transition);
      box-shadow: 0 4px 12px rgba(14,165,233,0.25);
    }

    .complete-sale-btn:hover { background: linear-gradient(135deg, #0284C7, #0369A1); box-shadow: 0 6px 16px rgba(14,165,233,0.35); }
    .complete-sale-btn:disabled { background: #CBD5E1; box-shadow: none; cursor: not-allowed; }

    /* Tables */
    .table-container {
      background: white;
      border-radius: var(--radius);
      box-shadow: var(--shadow-sm);
      border: 1px solid #EFF3F8;
      overflow-x: auto;
    }

    table { width: 100%; border-collapse: collapse; font-size: 0.85rem; }
    thead { background: #F8FAFC; border-bottom: 1px solid #E9EEF5; }

    th {
      text-align: left;
      padding: 0.75rem 1rem;
      font-weight: 600;
      color: var(--text-light);
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.3px;
      white-space: nowrap;
    }

    td { padding: 0.75rem 1rem; border-bottom: 1px solid #F1F5F9; color: var(--text); }
    tr:last-child td { border-bottom: none; }
    tr:hover td { background: #FAFCFE; }

    /* Filters */
    .filters-bar { display: flex; gap: 0.75rem; flex-wrap: wrap; margin-bottom: 1.25rem; align-items: center; }

    .filters-bar select,
    .filters-bar input {
      padding: 0.55rem 0.85rem;
      border: 1.5px solid #E2E8F0;
      border-radius: var(--radius-sm);
      font-size: 0.85rem;
      background: white;
      min-width: 140px;
    }

    .filters-bar select:focus,
    .filters-bar input:focus { outline: none; border-color: var(--primary); }

    /* Buttons */
    .btn {
      padding: 0.6rem 1.1rem;
      border-radius: var(--radius-sm);
      font-weight: 600;
      font-size: 0.85rem;
      transition: var(--transition);
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
    }

    .btn-primary { background: var(--primary); color: white; }
    .btn-primary:hover { background: var(--primary-dark); }

    .btn-outline { background: white; border: 1.5px solid #E2E8F0; color: var(--text); }
    .btn-outline:hover { border-color: var(--primary); color: var(--primary-dark); }

    .btn-danger { background: #FEF2F2; color: #DC2626; }
    .btn-danger:hover { background: #FEE2E2; }

    .btn-sm { padding: 0.4rem 0.75rem; font-size: 0.75rem; }

    /* Modal */
    .modal-overlay {
      position: fixed;
      inset: 0;
      background: rgba(15,23,42,0.5);
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 100;
      padding: 1rem;
      animation: fadeIn 0.2s ease;
    }

    @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }

    .modal {
      background: white;
      border-radius: var(--radius);
      box-shadow: var(--shadow-lg);
      width: 100%;
      max-width: 520px;
      max-height: 90vh;
      overflow-y: auto;
      animation: slideUp 0.25s ease;
    }

    @keyframes slideUp { from { transform: translateY(16px); opacity: 0; } to { transform: translateY(0); opacity: 1; } }

    .modal-header {
      padding: 1.25rem 1.5rem;
      border-bottom: 1px solid #EFF3F8;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .modal-header h3 { font-size: 1.1rem; font-weight: 700; }

    .modal-close {
      color: #94A3B8;
      font-size: 1.2rem;
      transition: var(--transition);
      width: 32px;
      height: 32px;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .modal-close:hover { background: #F1F5F9; color: var(--text); }
    .modal-body { padding: 1.5rem; }
    .modal-footer { padding: 1rem 1.5rem; border-top: 1px solid #EFF3F8; display: flex; gap: 0.75rem; justify-content: flex-end; }

    /* Receipt */
    .receipt {
      font-family: 'Courier New', monospace;
      font-size: 0.85rem;
      line-height: 1.6;
      color: #1E293B;
      background: #FAFCFE;
      padding: 1.5rem;
      border-radius: var(--radius-sm);
      border: 1px dashed #CBD5E1;
    }

    .receipt .shop-name { text-align: center; font-weight: 700; font-size: 1.1rem; letter-spacing: 1px; margin-bottom: 0.25rem; }
    .receipt .receipt-meta { text-align: center; font-size: 0.75rem; color: var(--text-light); margin-bottom: 1rem; }
    .receipt-divider { border-top: 1px dashed #CBD5E1; margin: 0.75rem 0; }
    .receipt .line-item { display: flex; justify-content: space-between; margin-bottom: 0.2rem; }

    .receipt .total-line {
      font-weight: 700;
      font-size: 1rem;
      display: flex;
      justify-content: space-between;
      margin-top: 0.5rem;
      padding-top: 0.5rem;
      border-top: 1px solid #CBD5E1;
    }

    .receipt .footer { text-align: center; margin-top: 1.25rem; font-size: 0.8rem; color: var(--text-light); }

    /* Toast */
    .toast-container {
      position: fixed;
      bottom: 1.5rem;
      right: 1.5rem;
      z-index: 200;
      display: flex;
      flex-direction: column;
      gap: 0.6rem;
      max-width: 360px;
      width: 100%;
      pointer-events: none;
    }

    .toast {
      background: white;
      border-radius: var(--radius-sm);
      box-shadow: var(--shadow-lg);
      padding: 0.9rem 1.1rem;
      display: flex;
      align-items: center;
      gap: 0.75rem;
      border-left: 4px solid var(--primary);
      animation: slideInRight 0.3s ease;
      pointer-events: auto;
    }

    @keyframes slideInRight { from { transform: translateX(100%); opacity: 0; } to { transform: translateX(0); opacity: 1; } }

    .toast.success { border-left-color: #22C55E; }
    .toast.error { border-left-color: #EF4444; }
    .toast.warning { border-left-color: #F59E0B; }
    .toast i { font-size: 1.1rem; }
    .toast.success i { color: #22C55E; }
    .toast.error i { color: #EF4444; }
    .toast.warning i { color: #F59E0B; }
    .toast .msg { font-size: 0.85rem; font-weight: 500; }

    /* Print */
    @media print {
      body * { visibility: hidden; }
      .modal-overlay.printing, .modal-overlay.printing * { visibility: visible; }
      .modal-overlay.printing { position: absolute; inset: 0; background: white; display: block; padding: 0; }
      .modal-overlay.printing .modal { max-width: 100%; box-shadow: none; border-radius: 0; }
      .modal-overlay.printing .modal-header,
      .modal-overlay.printing .modal-footer { display: none; }
      .modal-overlay.printing .modal-body { padding: 1rem; }
      .receipt { border: none; background: white; padding: 0; }
      .receipt .footer { margin-top: 2rem; }
    }

    /* Responsive */
    @media (max-width: 1024px) {
      .charts-grid { grid-template-columns: 1fr; }
      .pos-grid { grid-template-columns: 1fr; }
      .cart-panel { position: static; }
    }

    @media (max-width: 768px) {
      .sidebar { transform: translateX(-100%); width: 280px; }
      .sidebar.open { transform: translateX(0); }
      .main-content { margin-left: 0; padding: 1rem 1rem 5rem; }
      .menu-toggle { display: flex; }
      .page-header h1 { font-size: 1.25rem; }
      .stat-grid { grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); }
      .stat-card .value { font-size: 1.2rem; }
      .product-grid { grid-template-columns: repeat(auto-fill, minmax(120px, 1fr)); }
      .filters-bar { flex-direction: column; align-items: stretch; }
      .filters-bar select, .filters-bar input { width: 100%; }
      .modal { max-width: 100%; margin: 0.5rem; }
      .toast-container { left: 1rem; right: 1rem; bottom: 5rem; max-width: none; }
    }

    @media (max-width: 480px) {
      .stat-grid { grid-template-columns: 1fr 1fr; gap: 0.6rem; }
      .stat-card { padding: 0.9rem; }
      .stat-card .value { font-size: 1.1rem; }
      .pos-type-btn { min-width: 100%; font-size: 0.85rem; }
    }

    ::-webkit-scrollbar { width: 6px; height: 6px; }
    ::-webkit-scrollbar-track { background: transparent; }
    ::-webkit-scrollbar-thumb { background: #CBD5E1; border-radius: 10px; }
    ::-webkit-scrollbar-thumb:hover { background: #94A3B8; }
  </style>
</head>
<body>

  <div id="loginScreen" class="login-container">
    <div class="login-card">
      <div class="login-logo">
        <div class="logo-icon"><i class="fas fa-droplet"></i></div>
        <h1>PureFlow</h1>
        <p>Water Station POS</p>
      </div>
      <form id="loginForm" autocomplete="on">
        <div class="input-group">
          <label for="loginUsername">Username</label>
          <div class="input-wrapper">
            <input type="text" id="loginUsername" placeholder="Enter username" autocomplete="username">
          </div>
        </div>
        <div class="input-group">
          <label for="loginPassword">Password</label>
          <div class="input-wrapper">
            <input type="password" id="loginPassword" placeholder="Enter password" autocomplete="current-password">
            <i class="fas fa-eye" id="togglePassword" title="Show password"></i>
          </div>
        </div>
        <div class="login-options">
          <label>
            <input type="checkbox" id="rememberMe"> Remember me
          </label>
          <span class="text-light">Demo credentials below</span>
        </div>
        <button type="submit" class="login-btn">Sign In</button>
      </form>
      <div class="demo-hint">
        <strong>Admin:</strong> admin / admin123 &nbsp;·&nbsp; <strong>Attendant:</strong> attendant / 1234
      </div>
    </div>
  </div>

  <div id="appContainer" class="app-container hidden">
    <aside id="sidebar" class="sidebar">
      <div class="sidebar-header">
        <div class="logo-icon"><i class="fas fa-droplet"></i></div>
        <div>
          <h2>PureFlow</h2>
          <span>Water Station</span>
        </div>
      </div>
      <nav id="navMenu" class="nav-menu"></nav>
      <div class="sidebar-footer">
        <div class="user-info">
          <div class="user-avatar" id="userAvatar">A</div>
          <div class="user-details">
            <div class="name" id="userName">Admin</div>
            <div class="role" id="userRole">Administrator</div>
          </div>
        </div>
        <button class="logout-btn" id="logoutBtn">
          <i class="fas fa-sign-out-alt"></i> Logout
        </button>
      </div>
    </aside>
    <main id="mainContent" class="main-content">
      <div id="pageContent"></div>
    </main>
    <button class="menu-toggle" id="menuToggle">
      <i class="fas fa-bars"></i>
    </button>
  </div>

  <div id="modalRoot"></div>
  <div id="toastContainer" class="toast-container"></div>

  <script>
    'use strict';

    /* ============================================================
       SAFE STORAGE (handles sandboxed iframes / blocked localStorage)
       ============================================================ */
    const memoryStore = {};

    const safeStorage = {
      getItem(key) {
        try {
          const val = localStorage.getItem(key);
          if (val !== null) return val;
        } catch (e) { /* localStorage blocked */ }
        return memoryStore[key] !== undefined ? memoryStore[key] : null;
      },
      setItem(key, value) {
        try {
          localStorage.setItem(key, value);
        } catch (e) { /* localStorage blocked */ }
        memoryStore[key] = String(value);
      },
      removeItem(key) {
        try {
          localStorage.removeItem(key);
        } catch (e) { /* localStorage blocked */ }
        delete memoryStore[key];
      }
    };

    /* ============================================================
       ROUNDRECT POLYFILL
       ============================================================ */
    if (typeof CanvasRenderingContext2D !== 'undefined' &&
        !CanvasRenderingContext2D.prototype.roundRect) {
      CanvasRenderingContext2D.prototype.roundRect = function(x, y, w, h, radii) {
        if (typeof radii === 'number') radii = [radii];
        if (!Array.isArray(radii)) radii = [0];
        const r = radii.map(v => Math.min(Math.abs(v), w / 2, h / 2));
        const tl = r[0] || 0, tr = r[1] || r[0] || 0, br = r[2] || r[0] || 0, bl = r[3] || r[0] || 0;
        this.moveTo(x + tl, y);
        this.lineTo(x + w - tr, y);
        this.quadraticCurveTo(x + w, y, x + w, y + tr);
        this.lineTo(x + w, y + h - br);
        this.quadraticCurveTo(x + w, y + h, x + w - br, y + h);
        this.lineTo(x + bl, y + h);
        this.quadraticCurveTo(x, y + h, x, y + h - bl);
        this.lineTo(x, y + tl);
        this.quadraticCurveTo(x, y, x + tl, y);
        this.closePath();
        return this;
      };
    }

    /* ============================================================
       AUTHENTICATION
       ============================================================ */
    const DEMO_USERS = {
      admin: { password: 'admin123', name: 'Admin User', role: 'admin', roleLabel: 'Administrator' },
      attendant: { password: '1234', name: 'John Mwangi', role: 'attendant', roleLabel: 'Shop Attendant' }
    };

    let currentUser = null;

    function authenticate(username, password) {
      const key = String(username).toLowerCase().trim();
      const user = DEMO_USERS[key];
      if (user && user.password === password) {
        return { username: key, name: user.name, role: user.role, roleLabel: user.roleLabel };
      }
      return null;
    }

    function loginUser(user, remember) {
      currentUser = user;
      safeStorage.setItem('pf_currentUser', JSON.stringify(user));
      if (remember) {
        safeStorage.setItem('pf_rememberedUser', user.username);
      } else {
        safeStorage.removeItem('pf_rememberedUser');
      }
      showApp();
    }

    function logoutUser() {
      currentUser = null;
      safeStorage.removeItem('pf_currentUser');
      document.getElementById('appContainer').classList.add('hidden');
      document.getElementById('loginScreen').classList.remove('hidden');
      document.getElementById('loginForm').reset();
    }

    function checkSession() {
      try {
        const saved = safeStorage.getItem('pf_currentUser');
        if (saved) {
          const user = JSON.parse(saved);
          if (user && user.username) {
            currentUser = user;
            showApp();
            return true;
          }
        }
      } catch (e) { /* ignore */ }
      return false;
    }

    /* ============================================================
       STATE
       ============================================================ */
    const STORAGE_KEYS = {
      PRODUCTS: 'pf_products',
      TRANSACTIONS: 'pf_transactions',
      SETTINGS: 'pf_settings',
      CURRENT_USER: 'pf_currentUser',
      REMEMBERED_USER: 'pf_rememberedUser'
    };

    const DEFAULT_SETTINGS = {
      shopName: 'PureFlow Water Station',
      currency: 'KES',
      pricePerLiter: 5,
      lowStockThreshold: 10
    };

    const DEFAULT_PRODUCTS = [
      { id: 'p500', name: '500ml Bottle', size: 0.5, price: 30, stock: 85, lowStockLevel: 20, icon: 'fa-bottle-water' },
      { id: 'p1', name: '1L Bottle', size: 1, price: 50, stock: 120, lowStockLevel: 30, icon: 'fa-bottle-water' },
      { id: 'p5', name: '5L Bottle', size: 5, price: 100, stock: 45, lowStockLevel: 10, icon: 'fa-bottle-water' },
      { id: 'p10', name: '10L Bottle', size: 10, price: 180, stock: 38, lowStockLevel: 10, icon: 'fa-bottle-water' },
      { id: 'p20', name: '20L Bottle', size: 20, price: 300, stock: 24, lowStockLevel: 10, icon: 'fa-bottle-water' }
    ];

    let appState = {
      products: [],
      transactions: [],
      settings: { ...DEFAULT_SETTINGS },
      currentPage: 'dashboard',
      posMode: 'refill',
      cart: [],
      paymentMethod: 'Cash',
      refillContainerSize: '20',
      refillLiters: 20,
      filters: { dateRange: 'today', saleType: 'all', paymentMethod: 'all', attendant: 'all' }
    };

    function saveProducts() { safeStorage.setItem(STORAGE_KEYS.PRODUCTS, JSON.stringify(appState.products)); }
    function saveTransactions() { safeStorage.setItem(STORAGE_KEYS.TRANSACTIONS, JSON.stringify(appState.transactions)); }
    function saveSettings() { safeStorage.setItem(STORAGE_KEYS.SETTINGS, JSON.stringify(appState.settings)); }

    function loadState() {
      try {
        const savedProducts = safeStorage.getItem(STORAGE_KEYS.PRODUCTS);
        const savedTxns = safeStorage.getItem(STORAGE_KEYS.TRANSACTIONS);
        const savedSettings = safeStorage.getItem(STORAGE_KEYS.SETTINGS);

        if (savedProducts) {
          appState.products = JSON.parse(savedProducts);
        } else {
          appState.products = JSON.parse(JSON.stringify(DEFAULT_PRODUCTS));
          saveProducts();
        }

        if (savedSettings) {
          appState.settings = Object.assign({}, DEFAULT_SETTINGS, JSON.parse(savedSettings));
        } else {
          saveSettings();
        }

        if (savedTxns) {
          appState.transactions = JSON.parse(savedTxns);
        } else {
          generateDemoData();
        }
      } catch (e) {
        console.warn('Failed to load state, resetting.', e);
        try { resetDemoData(true); } catch (e2) { /* ignore */ }
      }
    }

    function generateDemoData() {
      const attendants = ['John Mwangi', 'Mary Wanjiku', 'Peter Otieno', 'Grace Akinyi'];
      const paymentMethods = ['Cash', 'M-Pesa', 'Card'];
      const now = new Date();
      const txns = [];
      let txnCounter = 120;

      for (let day = 6; day >= 0; day--) {
        const date = new Date(now);
        date.setDate(date.getDate() - day);
        const dateStr = date.toISOString().slice(0, 10);
        const txnsPerDay = day === 0 ? 8 : 6 + Math.floor(Math.random() * 5);

        for (let i = 0; i < txnsPerDay; i++) {
          txnCounter++;
          const isRefill = Math.random() > 0.4;
          const attendant = attendants[Math.floor(Math.random() * attendants.length)];
          const payment = paymentMethods[Math.floor(Math.random() * paymentMethods.length)];
          const hour = 7 + Math.floor(Math.random() * 12);
          const minute = Math.floor(Math.random() * 60);
          const ampm = hour >= 12 ? 'PM' : 'AM';
          const hour12 = hour > 12 ? hour - 12 : (hour === 0 ? 12 : hour);
          const timeStr = hour12 + ':' + String(minute).padStart(2, '0') + ' ' + ampm;

          const txn = {
            id: 'TXN-' + String(txnCounter).padStart(6, '0'),
            date: dateStr,
            time: timeStr,
            timestamp: date.getTime() + (hour * 3600000) + (minute * 60000),
            attendant: attendant,
            type: isRefill ? 'Customer Refill' : 'Pre-filled Bottle',
            liters: 0,
            quantity: 1,
            amount: 0,
            paymentMethod: payment,
            status: 'Completed',
            items: []
          };

          if (isRefill) {
            const sizes = [5, 10, 20];
            const containerSize = sizes[Math.floor(Math.random() * sizes.length)];
            const liters = containerSize;
            const amount = liters * appState.settings.pricePerLiter;
            txn.liters = liters;
            txn.amount = amount;
            txn.items = [{ name: containerSize + 'L Container', qty: 1, price: amount, liters: liters, type: 'refill' }];
          } else {
            const product = appState.products[Math.floor(Math.random() * appState.products.length)];
            const qty = Math.random() > 0.75 ? 2 : 1;
            const liters = product.size * qty;
            const amount = product.price * qty;
            txn.liters = liters;
            txn.quantity = qty;
            txn.amount = amount;
            txn.items = [{ name: product.name, qty: qty, price: product.price, liters: liters, type: 'prefilled' }];
          }

          txns.push(txn);
        }
      }

      appState.transactions = txns;
      saveTransactions();
    }

    function resetDemoData(silent) {
      appState.products = JSON.parse(JSON.stringify(DEFAULT_PRODUCTS));
      appState.transactions = [];
      appState.settings = Object.assign({}, DEFAULT_SETTINGS);
      appState.cart = [];
      appState.currentPage = 'dashboard';
      appState.posMode = 'refill';
      appState.paymentMethod = 'Cash';
      appState.refillContainerSize = '20';
      appState.refillLiters = 20;
      generateDemoData();
      saveProducts();
      saveSettings();
      saveTransactions();
      if (!silent) {
        showToast('Demo data reset successfully', 'success');
        renderCurrentPage();
      }
    }

    /* ============================================================
       UTILITIES
       ============================================================ */
    function formatCurrency(amount) {
      return appState.settings.currency + ' ' + Number(amount).toLocaleString('en-KE', { minimumFractionDigits: 0, maximumFractionDigits: 0 });
    }

    function formatLiters(liters) {
      return Number(liters).toLocaleString() + ' L';
    }

    function escapeHtml(str) {
      if (str === null || str === undefined) return '';
      const div = document.createElement('div');
      div.textContent = String(str);
      return div.innerHTML;
    }

    function generateId() {
      return 'TXN-' + String(Date.now()).slice(-6) + Math.floor(Math.random() * 100);
    }

    function getTodayString() { return new Date().toISOString().slice(0, 10); }

    function getWeekStart() {
      const d = new Date();
      const day = d.getDay();
      const diff = d.getDate() - day + (day === 0 ? -6 : 1);
      return new Date(d.setDate(diff)).toISOString().slice(0, 10);
    }

    function getMonthStart() {
      const d = new Date();
      return new Date(d.getFullYear(), d.getMonth(), 1).toISOString().slice(0, 10);
    }

    /* ============================================================
       DASHBOARD
       ============================================================ */
    function getDashboardStats() {
      const today = getTodayString();
      const todayTxns = appState.transactions.filter(t => t.date === today);
      const allTxns = appState.transactions;

      const todayRevenue = todayTxns.reduce((sum, t) => sum + t.amount, 0);
      const todayTransactions = todayTxns.length;
      const todayLiters = todayTxns.reduce((sum, t) => sum + t.liters, 0);
      const todayBottles = todayTxns.filter(t => t.type === 'Pre-filled Bottle').reduce((sum, t) => sum + (t.quantity || 1), 0);
      const totalStock = appState.products.reduce((sum, p) => sum + p.stock, 0);
      const lowStockItems = appState.products.filter(p => p.stock <= p.lowStockLevel).length;

      const last7Days = [];
      for (let i = 6; i >= 0; i--) {
        const d = new Date();
        d.setDate(d.getDate() - i);
        const dateStr = d.toISOString().slice(0, 10);
        const dayTxns = allTxns.filter(t => t.date === dateStr);
        last7Days.push({
          date: dateStr,
          label: d.toLocaleDateString('en', { weekday: 'short' }),
          liters: dayTxns.reduce((sum, t) => sum + t.liters, 0),
          revenue: dayTxns.reduce((sum, t) => sum + t.amount, 0)
        });
      }

      const refillLiters = todayTxns.filter(t => t.type === 'Customer Refill').reduce((s, t) => s + t.liters, 0);
      const prefilledLiters = todayTxns.filter(t => t.type === 'Pre-filled Bottle').reduce((s, t) => s + t.liters, 0);

      return { todayRevenue, todayTransactions, todayLiters, todayBottles, totalStock, lowStockItems, last7Days, refillLiters, prefilledLiters };
    }

    function renderDashboard() {
      const stats = getDashboardStats();
      const totalBreakdown = stats.refillLiters + stats.prefilledLiters || 1;
      const refillPct = Math.round((stats.refillLiters / totalBreakdown) * 100);
      const prefilledPct = 100 - refillPct;

      const html = `
        <div class="page-header">
          <div>
            <h1>Dashboard</h1>
            <div class="subtitle">Overview of today's performance</div>
          </div>
          <div class="text-sm text-light">
            <i class="far fa-calendar-alt"></i> ${new Date().toLocaleDateString('en', { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' })}
          </div>
        </div>

        <div class="stat-grid">
          <div class="stat-card">
            <div class="icon"><i class="fas fa-coins"></i></div>
            <div class="label">Today's Revenue</div>
            <div class="value">${formatCurrency(stats.todayRevenue)}</div>
            <div class="sub">${stats.todayTransactions} transactions</div>
          </div>
          <div class="stat-card">
            <div class="icon"><i class="fas fa-receipt"></i></div>
            <div class="label">Transactions</div>
            <div class="value">${stats.todayTransactions}</div>
            <div class="sub">Today</div>
          </div>
          <div class="stat-card">
            <div class="icon"><i class="fas fa-tint"></i></div>
            <div class="label">Water Dispensed</div>
            <div class="value">${formatLiters(stats.todayLiters)}</div>
            <div class="sub">Today</div>
          </div>
          <div class="stat-card">
            <div class="icon"><i class="fas fa-bottle-water"></i></div>
            <div class="label">Bottles Sold</div>
            <div class="value">${stats.todayBottles}</div>
            <div class="sub">Pre-filled bottles</div>
          </div>
          <div class="stat-card">
            <div class="icon"><i class="fas fa-warehouse"></i></div>
            <div class="label">Bottles in Stock</div>
            <div class="value">${stats.totalStock}</div>
            <div class="sub">All sizes</div>
          </div>
          <div class="stat-card">
            <div class="icon"><i class="fas fa-exclamation-triangle"></i></div>
            <div class="label">Low Stock Items</div>
            <div class="value" style="color:${stats.lowStockItems > 0 ? '#DC2626' : 'var(--text)'}">${stats.lowStockItems}</div>
            <div class="sub">Needs restocking</div>
          </div>
        </div>

        <div class="charts-grid">
          <div class="chart-card">
            <h3><i class="fas fa-chart-line" style="color:var(--primary);margin-right:6px;"></i> Water Sales (Last 7 Days)</h3>
            <div class="chart-container"><canvas id="waterChart"></canvas></div>
          </div>
          <div class="chart-card">
            <h3><i class="fas fa-chart-pie" style="color:var(--accent);margin-right:6px;"></i> Sales Breakdown</h3>
            <div class="chart-container" style="height:200px;"><canvas id="breakdownChart"></canvas></div>
            <div class="flex justify-between mt-2 text-xs">
              <span><span style="display:inline-block;width:8px;height:8px;border-radius:2px;background:#0EA5E9;margin-right:4px;"></span> Refill ${refillPct}%</span>
              <span><span style="display:inline-block;width:8px;height:8px;border-radius:2px;background:#14B8A6;margin-right:4px;"></span> Pre-filled ${prefilledPct}%</span>
            </div>
          </div>
        </div>

        <div class="card">
          <h3 style="font-size:0.95rem;font-weight:600;margin-bottom:0.75rem;"><i class="fas fa-boxes" style="color:var(--primary);margin-right:6px;"></i> Product Stock</h3>
          <div class="stock-list">
            ${appState.products.map(p => {
              const isLow = p.stock <= p.lowStockLevel;
              return `<div class="stock-item">
                <span class="size"><i class="fas ${p.icon}" style="color:var(--primary);width:16px;"></i> ${escapeHtml(p.name)}</span>
                <span class="qty ${isLow ? 'low' : ''}">${p.stock} units ${isLow ? '⚠️' : ''}</span>
              </div>`;
            }).join('')}
          </div>
        </div>
      `;

      document.getElementById('pageContent').innerHTML = html;
      drawWaterChart('waterChart', stats.last7Days);
      drawDonutChart('breakdownChart', [stats.refillLiters, stats.prefilledLiters]);
    }

    function drawWaterChart(canvasId, data) {
      const canvas = document.getElementById(canvasId);
      if (!canvas) return;
      const ctx = canvas.getContext('2d');
      const dpr = window.devicePixelRatio || 1;
      const rect = canvas.parentElement.getBoundingClientRect();
      canvas.width = rect.width * dpr;
      canvas.height = rect.height * dpr;
      canvas.style.width = rect.width + 'px';
      canvas.style.height = rect.height + 'px';
      ctx.scale(dpr, dpr);

      const w = rect.width;
      const h = rect.height;
      const padding = { top: 20, right: 16, bottom: 30, left: 45 };
      const chartW = w - padding.left - padding.right;
      const chartH = h - padding.top - padding.bottom;
      const maxVal = Math.max.apply(null, data.map(d => d.liters).concat([1]));
      const barWidth = Math.min(32, (chartW / data.length) * 0.5);
      const gap = (chartW - barWidth * data.length) / (data.length + 1);

      ctx.clearRect(0, 0, w, h);

      ctx.strokeStyle = '#F1F5F9';
      ctx.lineWidth = 1;
      for (let i = 0; i <= 4; i++) {
        const y = padding.top + (chartH / 4) * i;
        ctx.beginPath();
        ctx.moveTo(padding.left, y);
        ctx.lineTo(w - padding.right, y);
        ctx.stroke();
        ctx.fillStyle = '#94A3B8';
        ctx.font = '10px Inter, sans-serif';
        ctx.textAlign = 'right';
        const val = Math.round(maxVal * (1 - i / 4));
        ctx.fillText(val + 'L', padding.left - 6, y + 4);
      }

      data.forEach((d, i) => {
        const x = padding.left + gap + i * (barWidth + gap);
        const barH = (d.liters / maxVal) * chartH;
        const y = padding.top + chartH - barH;

        const gradient = ctx.createLinearGradient(0, y, 0, padding.top + chartH);
        gradient.addColorStop(0, '#0EA5E9');
        gradient.addColorStop(1, '#7DD3FC');

        ctx.fillStyle = gradient;
        ctx.beginPath();
        if (ctx.roundRect) {
          ctx.roundRect(x, y, barWidth, Math.max(barH, 1), [4, 4, 0, 0]);
        } else {
          ctx.rect(x, y, barWidth, Math.max(barH, 1));
        }
        ctx.fill();

        ctx.fillStyle = '#64748B';
        ctx.font = '10px Inter, sans-serif';
        ctx.textAlign = 'center';
        ctx.fillText(d.label, x + barWidth / 2, h - 6);
      });
    }

    function drawDonutChart(canvasId, values) {
      const canvas = document.getElementById(canvasId);
      if (!canvas) return;
      const ctx = canvas.getContext('2d');
      const dpr = window.devicePixelRatio || 1;
      const rect = canvas.parentElement.getBoundingClientRect();
      canvas.width = rect.width * dpr;
      canvas.height = rect.height * dpr;
      canvas.style.width = rect.width + 'px';
      canvas.style.height = rect.height + 'px';
      ctx.scale(dpr, dpr);

      const w = rect.width;
      const h = rect.height;
      const cx = w / 2;
      const cy = h / 2;
      const radius = Math.min(w, h) * 0.35;
      const innerRadius = radius * 0.6;
      const total = values.reduce((a, b) => a + b, 0) || 1;
      const colors = ['#0EA5E9', '#14B8A6'];
      const angles = values.map(v => (v / total) * Math.PI * 2);

      ctx.clearRect(0, 0, w, h);
      let startAngle = -Math.PI / 2;

      angles.forEach((angle, i) => {
        if (angle <= 0.001) return;
        ctx.beginPath();
        ctx.arc(cx, cy, radius, startAngle, startAngle + angle);
        ctx.arc(cx, cy, innerRadius, startAngle + angle, startAngle, true);
        ctx.closePath();
        ctx.fillStyle = colors[i];
        ctx.fill();

        const midAngle = startAngle + angle / 2;
        const labelR = radius * 0.8;
        const lx = cx + Math.cos(midAngle) * labelR;
        const ly = cy + Math.sin(midAngle) * labelR;
        const pct = Math.round((values[i] / total) * 100);
        if (pct > 5) {
          ctx.fillStyle = 'white';
          ctx.font = 'bold 12px Inter, sans-serif';
          ctx.textAlign = 'center';
          ctx.textBaseline = 'middle';
          ctx.fillText(pct + '%', lx, ly);
        }
        startAngle += angle;
      });

      ctx.fillStyle = '#0F172A';
      ctx.font = 'bold 14px Inter, sans-serif';
      ctx.textAlign = 'center';
      ctx.textBaseline = 'middle';
      ctx.fillText(total + 'L', cx, cy - 4);
      ctx.font = '10px Inter, sans-serif';
      ctx.fillStyle = '#94A3B8';
      ctx.fillText('Total', cx, cy + 14);
    }

    /* ============================================================
       POS
       ============================================================ */
    function renderPOS() {
      const isRefill = appState.posMode === 'refill';
      const cartTotal = appState.cart.reduce((sum, item) => sum + item.price * item.qty, 0);

      const html = `
        <div class="page-header">
          <div>
            <h1>Point of Sale</h1>
            <div class="subtitle">Process customer transactions</div>
          </div>
        </div>

        <div class="pos-type-selector">
          <button class="pos-type-btn ${isRefill ? 'active' : ''}" onclick="setPosMode('refill')">
            <i class="fas fa-tint"></i> Refill Customer Container
          </button>
          <button class="pos-type-btn ${!isRefill ? 'active' : ''}" onclick="setPosMode('prefilled')">
            <i class="fas fa-bottle-water"></i> Buy Pre-filled Bottle
          </button>
        </div>

        <div class="pos-grid">
          <div id="posMainArea">${isRefill ? renderRefillForm() : renderProductGrid()}</div>
          <div class="cart-panel">
            <div class="cart-header">
              <h3><i class="fas fa-shopping-cart" style="color:var(--primary);margin-right:6px;"></i> Cart</h3>
              <span class="badge badge-info">${appState.cart.length} items</span>
            </div>
            <div class="cart-items" id="cartItems">${renderCartItems()}</div>
            <div class="cart-footer">
              <div class="cart-totals">
                <div class="row"><span>Subtotal</span><span>${formatCurrency(cartTotal)}</span></div>
                <div class="row total"><span>Total</span><span>${formatCurrency(cartTotal)}</span></div>
              </div>
              <div class="payment-selector">
                <button class="payment-btn ${appState.paymentMethod === 'Cash' ? 'active' : ''}" onclick="setPaymentMethod('Cash')">Cash</button>
                <button class="payment-btn ${appState.paymentMethod === 'M-Pesa' ? 'active' : ''}" onclick="setPaymentMethod('M-Pesa')">M-Pesa</button>
                <button class="payment-btn ${appState.paymentMethod === 'Card' ? 'active' : ''}" onclick="setPaymentMethod('Card')">Card</button>
              </div>
              <button class="complete-sale-btn" onclick="completeSale()" ${appState.cart.length === 0 ? 'disabled' : ''}>
                <i class="fas fa-check-circle"></i> Complete Sale
              </button>
            </div>
          </div>
        </div>
      `;
      document.getElementById('pageContent').innerHTML = html;
    }

    function renderRefillForm() {
      const pricePerLiter = appState.settings.pricePerLiter;
      const liters = appState.refillLiters;
      const total = liters * pricePerLiter;

      return `
        <div class="refill-form">
          <div class="form-row">
            <label>Container Size</label>
            <select id="refillContainerSize" onchange="updateRefillSize(this.value)">
              <option value="5" ${appState.refillContainerSize === '5' ? 'selected' : ''}>5 Liters</option>
              <option value="10" ${appState.refillContainerSize === '10' ? 'selected' : ''}>10 Liters</option>
              <option value="20" ${appState.refillContainerSize === '20' ? 'selected' : ''}>20 Liters</option>
              <option value="custom" ${appState.refillContainerSize === 'custom' ? 'selected' : ''}>Custom</option>
            </select>
          </div>
          ${appState.refillContainerSize === 'custom' ? `
            <div class="form-row">
              <label>Custom Size (Liters)</label>
              <input type="number" id="customContainerSize" min="0.5" step="0.5" value="${liters}" onchange="updateCustomLiters(this.value)">
            </div>` : ''}
          <div class="form-row">
            <label>Liters Dispensed</label>
            <input type="number" id="refillLitersInput" min="0.5" step="0.5" value="${liters}" onchange="updateRefillLiters(this.value)">
          </div>
          <div class="refill-total">
            <div>
              <div class="label">Water Price</div>
              <div style="font-size:0.85rem;color:var(--text-light);">${formatCurrency(pricePerLiter)} / Liter</div>
            </div>
            <div class="amount" id="refillTotalDisplay">${formatCurrency(total)}</div>
          </div>
          <button class="btn btn-primary w-full" onclick="addRefillToCart()" style="justify-content:center;">
            <i class="fas fa-plus-circle"></i> Add Refill to Cart
          </button>
        </div>
      `;
    }

    function renderProductGrid() {
      return `
        <div class="product-grid">
          ${appState.products.map(p => {
            const isOut = p.stock <= 0;
            const isLow = p.stock <= p.lowStockLevel;
            return `
              <div class="product-card">
                <div class="icon-bottle"><i class="fas ${p.icon}"></i></div>
                <div class="name">${escapeHtml(p.name)}</div>
                <div class="price">${formatCurrency(p.price)}</div>
                <div class="stock ${isLow ? 'low' : ''}">${isOut ? 'Out of stock' : `Stock: ${p.stock}`}</div>
                <button class="add-btn" onclick="addProductToCart('${p.id}')" ${isOut ? 'disabled' : ''}>
                  ${isOut ? 'Unavailable' : 'Add to Cart'}
                </button>
              </div>`;
          }).join('')}
        </div>
      `;
    }

    function renderCartItems() {
      if (appState.cart.length === 0) {
        return `<div class="text-center text-light" style="padding:2rem 0;font-size:0.9rem;">
          <i class="fas fa-shopping-basket" style="font-size:1.5rem;display:block;margin-bottom:0.5rem;opacity:0.4;"></i>
          Cart is empty
        </div>`;
      }

      return appState.cart.map((item, index) => `
        <div class="cart-item">
          <div class="info">
            <div class="name">${escapeHtml(item.name)}</div>
            <div class="price">${formatCurrency(item.price)} × ${item.qty}</div>
          </div>
          <div class="qty-controls">
            <button class="qty-btn" onclick="updateCartQty(${index}, -1)">−</button>
            <span style="font-weight:600;font-size:0.85rem;min-width:20px;text-align:center;">${item.qty}</span>
            <button class="qty-btn" onclick="updateCartQty(${index}, 1)">+</button>
          </div>
          <div class="subtotal">${formatCurrency(item.price * item.qty)}</div>
          <button class="remove" onclick="removeFromCart(${index})"><i class="fas fa-times"></i></button>
        </div>
      `).join('');
    }

    function setPosMode(mode) { appState.posMode = mode; renderPOS(); }
    function setPaymentMethod(method) { appState.paymentMethod = method; renderPOS(); }

    function updateRefillSize(value) {
      appState.refillContainerSize = value;
      if (value !== 'custom') appState.refillLiters = parseInt(value);
      renderPOS();
    }

    function updateCustomLiters(value) {
      const val = parseFloat(value);
      if (val > 0) appState.refillLiters = val;
      renderPOS();
    }

    function updateRefillLiters(value) {
      const val = parseFloat(value);
      if (val > 0) {
        appState.refillLiters = val;
        if (appState.refillContainerSize !== 'custom') appState.refillContainerSize = 'custom';
      }
      renderPOS();
    }

    function addRefillToCart() {
      const liters = appState.refillLiters;
      if (!liters || liters <= 0) { showToast('Please enter a valid number of liters', 'error'); return; }
      const pricePerLiter = appState.settings.pricePerLiter;
      const total = liters * pricePerLiter;

      appState.cart.push({
        type: 'refill',
        name: liters + 'L Refill',
        price: total,
        qty: 1,
        liters: liters,
        unitPrice: pricePerLiter
      });

      showToast(liters + 'L refill added to cart', 'success');
      renderPOS();
    }

    function addProductToCart(productId) {
      const product = appState.products.find(p => p.id === productId);
      if (!product) return;

      const existing = appState.cart.find(item => item.productId === productId);
      const existingQty = existing ? existing.qty : 0;
      if (existingQty + 1 > product.stock) {
        showToast('Only ' + product.stock + ' units of ' + product.name + ' available', 'warning');
        return;
      }

      if (existing) {
        existing.qty += 1;
      } else {
        appState.cart.push({
          type: 'prefilled',
          productId: product.id,
          name: product.name,
          price: product.price,
          qty: 1,
          liters: product.size,
          unitPrice: product.price
        });
      }

      showToast(product.name + ' added to cart', 'success');
      renderPOS();
    }

    function updateCartQty(index, delta) {
      const item = appState.cart[index];
      if (!item) return;
      const newQty = item.qty + delta;
      if (newQty <= 0) { removeFromCart(index); return; }

      if (item.type === 'prefilled') {
        const product = appState.products.find(p => p.id === item.productId);
        if (product && newQty > product.stock) {
          showToast('Only ' + product.stock + ' units available', 'warning');
          return;
        }
      }

      item.qty = newQty;
      renderPOS();
    }

    function removeFromCart(index) { appState.cart.splice(index, 1); renderPOS(); }

    function completeSale() {
      if (appState.cart.length === 0) { showToast('Cart is empty', 'warning'); return; }

      for (const item of appState.cart) {
        if (item.type === 'prefilled') {
          const product = appState.products.find(p => p.id === item.productId);
          if (!product || product.stock < item.qty) {
            showToast('Insufficient stock for ' + item.name, 'error');
            return;
          }
        }
      }

      const now = new Date();
      const dateStr = now.toISOString().slice(0, 10);
      const hours = now.getHours();
      const minutes = now.getMinutes();
      const ampm = hours >= 12 ? 'PM' : 'AM';
      const hour12 = hours > 12 ? hours - 12 : (hours === 0 ? 12 : hours);
      const timeStr = hour12 + ':' + String(minutes).padStart(2, '0') + ' ' + ampm;

      const txnId = generateId();
      const totalAmount = appState.cart.reduce((sum, item) => sum + item.price * item.qty, 0);
      const totalLiters = appState.cart.reduce((sum, item) => sum + item.liters * item.qty, 0);

      appState.cart.forEach(item => {
        if (item.type === 'prefilled') {
          const product = appState.products.find(p => p.id === item.productId);
          if (product) product.stock -= item.qty;
        }
      });

      const hasRefill = appState.cart.some(i => i.type === 'refill');
      const hasPrefilled = appState.cart.some(i => i.type === 'prefilled');
      const saleType = hasRefill && hasPrefilled ? 'Mixed' : (hasRefill ? 'Customer Refill' : 'Pre-filled Bottle');

      const txn = {
        id: txnId,
        date: dateStr,
        time: timeStr,
        timestamp: now.getTime(),
        attendant: currentUser ? currentUser.name : 'Unknown',
        type: saleType,
        liters: totalLiters,
        quantity: appState.cart.reduce((sum, i) => sum + (i.type === 'prefilled' ? i.qty : 0), 0),
        amount: totalAmount,
        paymentMethod: appState.paymentMethod,
        status: 'Completed',
        items: appState.cart.map(i => ({ name: i.name, qty: i.qty, price: i.price, liters: i.liters, type: i.type }))
      };

      appState.transactions.unshift(txn);
      saveProducts();
      saveTransactions();

      showReceipt(txn);
      appState.cart = [];
      appState.paymentMethod = 'Cash';
      renderPOS();
    }

    /* ============================================================
       RECEIPT
       ============================================================ */
    function showReceipt(txn) {
      const receiptHtml = `
        <div class="receipt" id="receiptContent">
          <div class="shop-name">${escapeHtml(appState.settings.shopName.toUpperCase())}</div>
          <div class="receipt-meta">
            Transaction: ${escapeHtml(txn.id)}<br>
            Date: ${new Date(txn.date).toLocaleDateString('en', { day: 'numeric', month: 'short', year: 'numeric' })}<br>
            Time: ${escapeHtml(txn.time)}
          </div>
          <div class="receipt-divider"></div>
          ${txn.items.map(item => `
            <div class="line-item">
              <span>${escapeHtml(item.name)} ${item.qty > 1 ? '× ' + item.qty : ''}</span>
              <span>${formatCurrency(item.price * item.qty)}</span>
            </div>
            ${item.type === 'refill' ? `<div class="line-item" style="font-size:0.8rem;color:var(--text-light);"><span>Water: ${item.liters}L</span><span></span></div>` : ''}
          `).join('')}
          <div class="receipt-divider"></div>
          <div class="line-item"><span>Water: ${txn.liters}L</span><span></span></div>
          <div class="line-item"><span>Payment: ${escapeHtml(txn.paymentMethod)}</span><span></span></div>
          <div class="total-line"><span>TOTAL</span><span>${formatCurrency(txn.amount)}</span></div>
          <div class="footer">Thank you for your business!<br><span style="font-size:0.7rem;">Powered by PureFlow POS</span></div>
        </div>
      `;

      const modalHtml = `
        <div class="modal-overlay" id="receiptModal">
          <div class="modal">
            <div class="modal-header">
              <h3><i class="fas fa-receipt" style="color:var(--primary);margin-right:6px;"></i> Receipt</h3>
              <button class="modal-close" onclick="closeModal('receiptModal')"><i class="fas fa-times"></i></button>
            </div>
            <div class="modal-body">${receiptHtml}</div>
            <div class="modal-footer">
              <button class="btn btn-outline" onclick="closeModal('receiptModal')">Close</button>
              <button class="btn btn-primary" onclick="printReceipt()"><i class="fas fa-print"></i> Print Receipt</button>
            </div>
          </div>
        </div>
      `;

      document.getElementById('modalRoot').innerHTML = modalHtml;
    }

    function printReceipt() {
      const modal = document.getElementById('receiptModal');
      if (!modal) return;
      modal.classList.add('printing');
      window.print();
      setTimeout(() => modal.classList.remove('printing'), 500);
    }

    function closeModal(id) {
      const el = document.getElementById(id);
      if (el) el.remove();
    }

    /* ============================================================
       INVENTORY
       ============================================================ */
    function renderProductsStock() {
      const html = `
        <div class="page-header">
          <div>
            <h1>Products & Stock</h1>
            <div class="subtitle">Manage bottle inventory</div>
          </div>
          <button class="btn btn-primary" onclick="showAddProductModal()"><i class="fas fa-plus"></i> Add Product</button>
        </div>
        <div class="table-container">
          <table>
            <thead>
              <tr>
                <th>Product</th><th>Bottle Size</th><th>Price</th><th>Current Stock</th>
                <th>Low Stock Level</th><th>Status</th><th>Actions</th>
              </tr>
            </thead>
            <tbody>
              ${appState.products.map(p => {
                const isLow = p.stock <= p.lowStockLevel;
                const isOut = p.stock <= 0;
                return `<tr>
                  <td><strong>${escapeHtml(p.name)}</strong></td>
                  <td>${p.size}L</td>
                  <td>${formatCurrency(p.price)}</td>
                  <td>${p.stock}</td>
                  <td>${p.lowStockLevel}</td>
                  <td><span class="badge ${isOut ? 'badge-danger' : (isLow ? 'badge-warning' : 'badge-success')}">
                    ${isOut ? 'Out of Stock' : (isLow ? 'Low Stock' : 'In Stock')}
                  </span></td>
                  <td><button class="btn btn-sm btn-outline" onclick="showAdjustStockModal('${p.id}')"><i class="fas fa-sliders-h"></i> Adjust</button></td>
                </tr>`;
              }).join('')}
            </tbody>
          </table>
        </div>
      `;
      document.getElementById('pageContent').innerHTML = html;
    }

    function showAddProductModal() {
      const modalHtml = `
        <div class="modal-overlay" id="addProductModal">
          <div class="modal">
            <div class="modal-header">
              <h3>Add Product</h3>
              <button class="modal-close" onclick="closeModal('addProductModal')"><i class="fas fa-times"></i></button>
            </div>
            <div class="modal-body">
              <div style="margin-bottom:1rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Product Name</label>
                <input type="text" id="newProductName" placeholder="e.g. 2L Bottle" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
              <div style="margin-bottom:1rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Bottle Size (Liters)</label>
                <input type="number" id="newProductSize" min="0.1" step="0.1" placeholder="e.g. 2" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
              <div style="margin-bottom:1rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Price (KES)</label>
                <input type="number" id="newProductPrice" min="1" step="1" placeholder="e.g. 80" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
              <div style="margin-bottom:1rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Initial Stock</label>
                <input type="number" id="newProductStock" min="0" step="1" placeholder="e.g. 50" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
              <div style="margin-bottom:1rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Low Stock Level</label>
                <input type="number" id="newProductLow" min="1" step="1" value="10" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
            </div>
            <div class="modal-footer">
              <button class="btn btn-outline" onclick="closeModal('addProductModal')">Cancel</button>
              <button class="btn btn-primary" onclick="addProduct()">Add Product</button>
            </div>
          </div>
        </div>
      `;
      document.getElementById('modalRoot').innerHTML = modalHtml;
    }

    function addProduct() {
      const name = document.getElementById('newProductName').value.trim();
      const size = parseFloat(document.getElementById('newProductSize').value);
      const price = parseFloat(document.getElementById('newProductPrice').value);
      const stock = parseInt(document.getElementById('newProductStock').value);
      const lowStockLevel = parseInt(document.getElementById('newProductLow').value) || 10;

      if (!name || !size || size <= 0 || !price || price <= 0 || isNaN(stock) || stock < 0) {
        showToast('Please fill in all fields with valid values', 'error');
        return;
      }

      appState.products.push({ id: 'p' + size + '_' + Date.now(), name, size, price, stock, lowStockLevel, icon: 'fa-bottle-water' });
      saveProducts();
      closeModal('addProductModal');
      showToast(name + ' added successfully', 'success');
      renderProductsStock();
    }

    function showAdjustStockModal(productId) {
      const product = appState.products.find(p => p.id === productId);
      if (!product) return;

      const modalHtml = `
        <div class="modal-overlay" id="adjustStockModal">
          <div class="modal">
            <div class="modal-header">
              <h3>Adjust Stock — ${escapeHtml(product.name)}</h3>
              <button class="modal-close" onclick="closeModal('adjustStockModal')"><i class="fas fa-times"></i></button>
            </div>
            <div class="modal-body">
              <p class="text-sm text-light mb-2">Current stock: <strong>${product.stock}</strong> units</p>
              <div style="margin-bottom:1rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Adjustment Type</label>
                <select id="adjustType" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;">
                  <option value="received">Stock Received</option>
                  <option value="damaged">Damaged Bottles</option>
                  <option value="manual">Manual Adjustment</option>
                </select></div>
              <div style="margin-bottom:1rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Quantity</label>
                <input type="number" id="adjustQty" min="1" step="1" value="1" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
            </div>
            <div class="modal-footer">
              <button class="btn btn-outline" onclick="closeModal('adjustStockModal')">Cancel</button>
              <button class="btn btn-primary" onclick="adjustStock('${product.id}')">Confirm Adjustment</button>
            </div>
          </div>
        </div>
      `;
      document.getElementById('modalRoot').innerHTML = modalHtml;
    }

    function adjustStock(productId) {
      const product = appState.products.find(p => p.id === productId);
      if (!product) return;
      const type = document.getElementById('adjustType').value;
      const qty = parseInt(document.getElementById('adjustQty').value);
      if (!qty || qty <= 0) { showToast('Please enter a valid quantity', 'error'); return; }

      let newStock = product.stock;
      if (type === 'received') newStock += qty;
      else if (type === 'damaged') newStock = Math.max(0, newStock - qty);
      else newStock = qty;

      product.stock = newStock;
      saveProducts();
      closeModal('adjustStockModal');
      showToast('Stock adjusted: ' + product.name + ' is now ' + newStock + ' units', 'success');
      renderProductsStock();
    }

    /* ============================================================
       SALES HISTORY
       ============================================================ */
    function renderSalesHistory() {
      const filtered = getFilteredTransactions();
      const isAttendant = currentUser && currentUser.role === 'attendant';

      const html = `
        <div class="page-header">
          <div>
            <h1>${isAttendant ? "Today's Sales" : 'Sales History'}</h1>
            <div class="subtitle">${filtered.length} transactions found</div>
          </div>
        </div>

        ${!isAttendant ? `
        <div class="filters-bar">
          <select onchange="updateFilter('dateRange', this.value)">
            <option value="today" ${appState.filters.dateRange === 'today' ? 'selected' : ''}>Today</option>
            <option value="week" ${appState.filters.dateRange === 'week' ? 'selected' : ''}>This Week</option>
            <option value="month" ${appState.filters.dateRange === 'month' ? 'selected' : ''}>This Month</option>
            <option value="all" ${appState.filters.dateRange === 'all' ? 'selected' : ''}>All Time</option>
          </select>
          <select onchange="updateFilter('saleType', this.value)">
            <option value="all" ${appState.filters.saleType === 'all' ? 'selected' : ''}>All Types</option>
            <option value="Customer Refill" ${appState.filters.saleType === 'Customer Refill' ? 'selected' : ''}>Customer Refill</option>
            <option value="Pre-filled Bottle" ${appState.filters.saleType === 'Pre-filled Bottle' ? 'selected' : ''}>Pre-filled Bottle</option>
          </select>
          <select onchange="updateFilter('paymentMethod', this.value)">
            <option value="all" ${appState.filters.paymentMethod === 'all' ? 'selected' : ''}>All Payments</option>
            <option value="Cash" ${appState.filters.paymentMethod === 'Cash' ? 'selected' : ''}>Cash</option>
            <option value="M-Pesa" ${appState.filters.paymentMethod === 'M-Pesa' ? 'selected' : ''}>M-Pesa</option>
            <option value="Card" ${appState.filters.paymentMethod === 'Card' ? 'selected' : ''}>Card</option>
          </select>
          <select onchange="updateFilter('attendant', this.value)">
            <option value="all" ${appState.filters.attendant === 'all' ? 'selected' : ''}>All Attendants</option>
            <option value="John Mwangi" ${appState.filters.attendant === 'John Mwangi' ? 'selected' : ''}>John Mwangi</option>
            <option value="Mary Wanjiku" ${appState.filters.attendant === 'Mary Wanjiku' ? 'selected' : ''}>Mary Wanjiku</option>
            <option value="Peter Otieno" ${appState.filters.attendant === 'Peter Otieno' ? 'selected' : ''}>Peter Otieno</option>
            <option value="Grace Akinyi" ${appState.filters.attendant === 'Grace Akinyi' ? 'selected' : ''}>Grace Akinyi</option>
          </select>
        </div>` : ''}

        <div class="table-container">
          <table>
            <thead>
              <tr>
                <th>Transaction ID</th><th>Date</th><th>Time</th><th>Attendant</th><th>Sale Type</th>
                <th>Product/Container</th><th>Liters</th><th>Qty</th><th>Amount</th><th>Payment</th><th>Status</th>
              </tr>
            </thead>
            <tbody>
              ${filtered.length === 0 ? `<tr><td colspan="11" class="text-center text-light" style="padding:2rem;">No transactions found</td></tr>` :
              filtered.map(t => `<tr>
                <td><strong>${escapeHtml(t.id)}</strong></td>
                <td>${new Date(t.date).toLocaleDateString('en', { day: 'numeric', month: 'short', year: 'numeric' })}</td>
                <td>${escapeHtml(t.time)}</td>
                <td>${escapeHtml(t.attendant)}</td>
                <td><span class="badge ${t.type === 'Customer Refill' ? 'badge-info' : (t.type === 'Pre-filled Bottle' ? 'badge-success' : 'badge-warning')}">${escapeHtml(t.type)}</span></td>
                <td>${t.items.map(i => escapeHtml(i.name)).join(', ')}</td>
                <td>${t.liters}L</td>
                <td>${t.quantity || 1}</td>
                <td><strong>${formatCurrency(t.amount)}</strong></td>
                <td>${escapeHtml(t.paymentMethod)}</td>
                <td><span class="badge badge-success">${escapeHtml(t.status)}</span></td>
              </tr>`).join('')}
            </tbody>
          </table>
        </div>
      `;
      document.getElementById('pageContent').innerHTML = html;
    }

    function updateFilter(key, value) {
      appState.filters[key] = value;
      renderSalesHistory();
    }

    function getFilteredTransactions() {
      let txns = appState.transactions.slice();
      const today = getTodayString();

      if (appState.filters.dateRange === 'today') txns = txns.filter(t => t.date === today);
      else if (appState.filters.dateRange === 'week') { const ws = getWeekStart(); txns = txns.filter(t => t.date >= ws); }
      else if (appState.filters.dateRange === 'month') { const ms = getMonthStart(); txns = txns.filter(t => t.date >= ms); }

      if (appState.filters.saleType !== 'all') txns = txns.filter(t => t.type === appState.filters.saleType);
      if (appState.filters.paymentMethod !== 'all') txns = txns.filter(t => t.paymentMethod === appState.filters.paymentMethod);
      if (appState.filters.attendant !== 'all') txns = txns.filter(t => t.attendant === appState.filters.attendant);
      if (currentUser && currentUser.role === 'attendant') txns = txns.filter(t => t.date === today);

      return txns.sort((a, b) => b.timestamp - a.timestamp);
    }

    /* ============================================================
       REPORTS
       ============================================================ */
    function renderReports() {
      const allTxns = appState.transactions;
      const totalLiters = allTxns.reduce((s, t) => s + t.liters, 0);
      const refillLiters = allTxns.filter(t => t.type === 'Customer Refill').reduce((s, t) => s + t.liters, 0);
      const prefilledLiters = allTxns.filter(t => t.type === 'Pre-filled Bottle').reduce((s, t) => s + t.liters, 0);
      const cashRevenue = allTxns.filter(t => t.paymentMethod === 'Cash').reduce((s, t) => s + t.amount, 0);
      const mpesaRevenue = allTxns.filter(t => t.paymentMethod === 'M-Pesa').reduce((s, t) => s + t.amount, 0);
      const cardRevenue = allTxns.filter(t => t.paymentMethod === 'Card').reduce((s, t) => s + t.amount, 0);
      const totalRevenue = cashRevenue + mpesaRevenue + cardRevenue;
      const bottlesSold = allTxns.filter(t => t.type === 'Pre-filled Bottle').reduce((s, t) => s + (t.quantity || 1), 0);
      const currentStock = appState.products.reduce((s, p) => s + p.stock, 0);

      const html = `
        <div class="page-header">
          <div>
            <h1>Reports</h1>
            <div class="subtitle">Business performance summary</div>
          </div>
          <button class="btn btn-primary" onclick="exportReport()"><i class="fas fa-download"></i> Export Report</button>
        </div>

        <div class="stat-grid">
          <div class="stat-card"><div class="label">Total Liters Dispensed</div><div class="value">${formatLiters(totalLiters)}</div></div>
          <div class="stat-card"><div class="label">Customer Refills</div><div class="value">${formatLiters(refillLiters)}</div></div>
          <div class="stat-card"><div class="label">Pre-filled Bottles</div><div class="value">${formatLiters(prefilledLiters)}</div></div>
          <div class="stat-card"><div class="label">Total Revenue</div><div class="value">${formatCurrency(totalRevenue)}</div></div>
        </div>

        <div class="charts-grid">
          <div class="chart-card">
            <h3><i class="fas fa-chart-bar" style="color:var(--primary);margin-right:6px;"></i> Revenue by Payment Method</h3>
            <div class="chart-container" style="height:180px;"><canvas id="revenueChart"></canvas></div>
            <div class="flex justify-between mt-2 text-xs">
              <span>Cash: ${formatCurrency(cashRevenue)}</span>
              <span>M-Pesa: ${formatCurrency(mpesaRevenue)}</span>
              <span>Card: ${formatCurrency(cardRevenue)}</span>
            </div>
          </div>
          <div class="chart-card">
            <h3><i class="fas fa-boxes" style="color:var(--accent);margin-right:6px;"></i> Bottle Inventory</h3>
            <div class="stock-list" style="margin-top:0.5rem;">
              <div class="stock-item"><span class="size">Opening Stock</span><span class="qty">${currentStock + bottlesSold}</span></div>
              <div class="stock-item"><span class="size">Stock Received</span><span class="qty">0</span></div>
              <div class="stock-item"><span class="size">Bottles Sold</span><span class="qty">${bottlesSold}</span></div>
              <div class="stock-item"><span class="size">Damaged</span><span class="qty">0</span></div>
              <div class="stock-item" style="border-top:1px solid #E2E8F0;margin-top:0.25rem;padding-top:0.55rem;">
                <span class="size" style="font-weight:700;">Current Stock</span>
                <span class="qty" style="font-weight:700;color:var(--primary-dark);">${currentStock}</span>
              </div>
            </div>
          </div>
        </div>

        <div class="card">
          <h3 style="font-size:0.95rem;font-weight:600;margin-bottom:0.75rem;"><i class="fas fa-chart-pie" style="color:var(--accent);margin-right:6px;"></i> Water Sales Breakdown</h3>
          <div class="stock-list">
            <div class="stock-item"><span class="size">Customer Refills</span><span class="qty">${formatLiters(refillLiters)}</span></div>
            <div class="stock-item"><span class="size">Pre-filled Bottles</span><span class="qty">${formatLiters(prefilledLiters)}</span></div>
            <div class="stock-item" style="border-top:1px solid #E2E8F0;margin-top:0.25rem;padding-top:0.55rem;">
              <span class="size" style="font-weight:700;">Total</span>
              <span class="qty" style="font-weight:700;color:var(--primary-dark);">${formatLiters(totalLiters)}</span>
            </div>
          </div>
        </div>
      `;
      document.getElementById('pageContent').innerHTML = html;
      drawRevenueChart('revenueChart', [cashRevenue, mpesaRevenue, cardRevenue]);
    }

    function drawRevenueChart(canvasId, values) {
      const canvas = document.getElementById(canvasId);
      if (!canvas) return;
      const ctx = canvas.getContext('2d');
      const dpr = window.devicePixelRatio || 1;
      const rect = canvas.parentElement.getBoundingClientRect();
      canvas.width = rect.width * dpr;
      canvas.height = rect.height * dpr;
      canvas.style.width = rect.width + 'px';
      canvas.style.height = rect.height + 'px';
      ctx.scale(dpr, dpr);

      const w = rect.width;
      const h = rect.height;
      const padding = { top: 16, right: 16, bottom: 28, left: 50 };
      const chartW = w - padding.left - padding.right;
      const chartH = h - padding.top - padding.bottom;
      const labels = ['Cash', 'M-Pesa', 'Card'];
      const colors = ['#0EA5E9', '#14B8A6', '#F59E0B'];
      const maxVal = Math.max.apply(null, values.concat([1]));
      const barWidth = Math.min(48, (chartW / values.length) * 0.5);
      const gap = (chartW - barWidth * values.length) / (values.length + 1);

      ctx.clearRect(0, 0, w, h);

      ctx.strokeStyle = '#F1F5F9';
      ctx.lineWidth = 1;
      for (let i = 0; i <= 3; i++) {
        const y = padding.top + (chartH / 3) * i;
        ctx.beginPath();
        ctx.moveTo(padding.left, y);
        ctx.lineTo(w - padding.right, y);
        ctx.stroke();
        ctx.fillStyle = '#94A3B8';
        ctx.font = '10px Inter, sans-serif';
        ctx.textAlign = 'right';
        const val = Math.round(maxVal * (1 - i / 3));
        ctx.fillText(formatCurrency(val).replace('KES ', ''), padding.left - 6, y + 4);
      }

      values.forEach((val, i) => {
        const x = padding.left + gap + i * (barWidth + gap);
        const barH = (val / maxVal) * chartH;
        const y = padding.top + chartH - barH;

        ctx.fillStyle = colors[i];
        ctx.beginPath();
        if (ctx.roundRect) {
          ctx.roundRect(x, y, barWidth, Math.max(barH, 1), [4, 4, 0, 0]);
        } else {
          ctx.rect(x, y, barWidth, Math.max(barH, 1));
        }
        ctx.fill();

        ctx.fillStyle = '#64748B';
        ctx.font = '10px Inter, sans-serif';
        ctx.textAlign = 'center';
        ctx.fillText(labels[i], x + barWidth / 2, h - 6);
      });
    }

    function exportReport() {
      const allTxns = appState.transactions;
      if (allTxns.length === 0) { showToast('No data to export', 'warning'); return; }

      const headers = ['Transaction ID', 'Date', 'Time', 'Attendant', 'Sale Type', 'Product', 'Liters', 'Qty', 'Amount', 'Payment Method', 'Status'];
      const rows = allTxns.map(t => [
        t.id, t.date, t.time, t.attendant, t.type,
        t.items.map(i => i.name).join('; '),
        t.liters, t.quantity || 1, t.amount, t.paymentMethod, t.status
      ]);

      let csv = headers.join(',') + '\n';
      rows.forEach(row => {
        csv += row.map(v => {
          const s = String(v);
          return s.includes(',') || s.includes('"') ? '"' + s.replace(/"/g, '""') + '"' : s;
        }).join(',') + '\n';
      });

      const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
      const link = document.createElement('a');
      link.href = URL.createObjectURL(blob);
      link.download = 'pureflow_report_' + getTodayString() + '.csv';
      link.click();
      URL.revokeObjectURL(link.href);
      showToast('Report exported as CSV', 'success');
    }

    /* ============================================================
       SETTINGS
       ============================================================ */
    function renderSettings() {
      const html = `
        <div class="page-header">
          <div>
            <h1>Settings</h1>
            <div class="subtitle">Configure your POS system</div>
          </div>
        </div>

        <div class="card" style="max-width:640px;">
          <div style="margin-bottom:1.25rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Shop Name</label>
            <input type="text" id="settingShopName" value="${escapeHtml(appState.settings.shopName)}" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
          <div style="margin-bottom:1.25rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Currency</label>
            <input type="text" id="settingCurrency" value="${escapeHtml(appState.settings.currency)}" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
          <div style="margin-bottom:1.25rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Price per Liter (KES)</label>
            <input type="number" id="settingPricePerLiter" value="${appState.settings.pricePerLiter}" min="1" step="1" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
          <div style="margin-bottom:1.5rem;"><label style="display:block;font-size:0.85rem;font-weight:500;margin-bottom:0.35rem;">Low Stock Threshold</label>
            <input type="number" id="settingLowStock" value="${appState.settings.lowStockThreshold}" min="1" step="1" style="width:100%;padding:0.7rem 1rem;border:1.5px solid #E2E8F0;border-radius:8px;font-size:0.95rem;"></div>
          <button class="btn btn-primary" onclick="saveSettings()"><i class="fas fa-save"></i> Save Settings</button>
        </div>

        <div class="card" style="max-width:640px;margin-top:1.5rem;border-color:#FEE2E2;">
          <h3 style="font-size:0.95rem;font-weight:600;color:#DC2626;margin-bottom:0.5rem;"><i class="fas fa-exclamation-triangle"></i> Danger Zone</h3>
          <p class="text-sm text-light mb-2">Reset all demo data back to the original sample state. This cannot be undone.</p>
          <button class="btn btn-danger" onclick="confirmResetDemo()"><i class="fas fa-undo"></i> Reset Demo Data</button>
        </div>
      `;
      document.getElementById('pageContent').innerHTML = html;
    }

    function saveSettings() {
      const shopName = document.getElementById('settingShopName').value.trim();
      const currency = document.getElementById('settingCurrency').value.trim();
      const pricePerLiter = parseFloat(document.getElementById('settingPricePerLiter').value);
      const lowStockThreshold = parseInt(document.getElementById('settingLowStock').value);

      if (!shopName || !currency || !pricePerLiter || pricePerLiter <= 0 || !lowStockThreshold || lowStockThreshold < 1) {
        showToast('Please fill in all fields with valid values', 'error');
        return;
      }

      appState.settings = { shopName, currency, pricePerLiter, lowStockThreshold };
      saveSettings();
      showToast('Settings saved successfully', 'success');
    }

    function confirmResetDemo() {
      if (confirm('Are you sure you want to reset all demo data? This will erase all transactions and restore default products.')) {
        resetDemoData(false);
      }
    }

    /* ============================================================
       NAVIGATION
       ============================================================ */
    function getNavItems() {
      if (!currentUser) return [];
      const isAdmin = currentUser.role === 'admin';
      const items = [];
      if (isAdmin) items.push({ id: 'dashboard', label: 'Dashboard', icon: 'fa-chart-pie' });
      items.push({ id: 'pos', label: 'POS', icon: 'fa-cash-register' });
      if (isAdmin) {
        items.push({ id: 'sales', label: 'Sales', icon: 'fa-receipt' });
        items.push({ id: 'products', label: 'Products & Stock', icon: 'fa-boxes' });
        items.push({ id: 'reports', label: 'Reports', icon: 'fa-chart-line' });
        items.push({ id: 'settings', label: 'Settings', icon: 'fa-cog' });
      } else {
        items.push({ id: 'sales', label: "Today's Sales", icon: 'fa-receipt' });
      }
      return items;
    }

    function navigateTo(pageId) {
      appState.currentPage = pageId;
      updateSidebar();
      renderCurrentPage();
      document.getElementById('sidebar').classList.remove('open');
    }

    function updateSidebar() {
      const navItems = getNavItems();
      document.getElementById('navMenu').innerHTML = navItems.map(item => `
        <div class="nav-item ${appState.currentPage === item.id ? 'active' : ''}" onclick="navigateTo('${item.id}')">
          <i class="fas ${item.icon}"></i><span>${item.label}</span>
        </div>
      `).join('');
    }

    function renderCurrentPage() {
      const page = appState.currentPage;
      if (!currentUser) return;

      if (page === 'dashboard' && currentUser.role === 'admin') renderDashboard();
      else if (page === 'pos') renderPOS();
      else if (page === 'sales') renderSalesHistory();
      else if (page === 'products' && currentUser.role === 'admin') renderProductsStock();
      else if (page === 'reports' && currentUser.role === 'admin') renderReports();
      else if (page === 'settings' && currentUser.role === 'admin') renderSettings();
      else {
        if (currentUser.role === 'admin') navigateTo('dashboard');
        else navigateTo('pos');
      }
    }

    /* ============================================================
       TOASTS
       ============================================================ */
    function showToast(message, type) {
      type = type || 'info';
      const container = document.getElementById('toastContainer');
      const toast = document.createElement('div');
      toast.className = 'toast ' + type;

      const icons = { success: 'fa-check-circle', error: 'fa-exclamation-circle', warning: 'fa-exclamation-triangle', info: 'fa-info-circle' };
      toast.innerHTML = '<i class="fas ' + (icons[type] || icons.info) + '"></i><span class="msg">' + escapeHtml(message) + '</span>';
      container.appendChild(toast);

      setTimeout(() => {
        toast.style.opacity = '0';
        toast.style.transform = 'translateX(100%)';
        toast.style.transition = 'all 0.3s ease';
        setTimeout(() => toast.remove(), 300);
      }, 3500);
    }

    /* ============================================================
       APP INIT
       ============================================================ */
    function showApp() {
      document.getElementById('loginScreen').classList.add('hidden');
      document.getElementById('appContainer').classList.remove('hidden');

      if (currentUser) {
        document.getElementById('userAvatar').textContent = currentUser.name.charAt(0).toUpperCase();
        document.getElementById('userName').textContent = currentUser.name;
        document.getElementById('userRole').textContent = currentUser.roleLabel;
        appState.currentPage = currentUser.role === 'admin' ? 'dashboard' : 'pos';
      }

      updateSidebar();
      renderCurrentPage();
    }

    function handleLogin(e) {
      e.preventDefault();
      const username = document.getElementById('loginUsername').value.trim();
      const password = document.getElementById('loginPassword').value;
      const remember = document.getElementById('rememberMe').checked;

      if (!username || !password) { showToast('Please enter both username and password', 'error'); return; }

      const user = authenticate(username, password);
      if (!user) { showToast('Invalid username or password', 'error'); return; }

      loginUser(user, remember);
      showToast('Welcome back, ' + user.name + '!', 'success');
    }

    function togglePasswordVisibility() {
      const input = document.getElementById('loginPassword');
      const icon = document.getElementById('togglePassword');
      if (input.type === 'password') {
        input.type = 'text';
        icon.classList.remove('fa-eye');
        icon.classList.add('fa-eye-slash');
      } else {
        input.type = 'password';
        icon.classList.remove('fa-eye-slash');
        icon.classList.add('fa-eye');
      }
    }

    /* ---------- Boot ---------- */
    document.addEventListener('DOMContentLoaded', function() {
      try { loadState(); } catch (e) { console.warn('loadState error', e); }

      try {
        if (!checkSession()) {
          const remembered = safeStorage.getItem(STORAGE_KEYS.REMEMBERED_USER);
          if (remembered) {
            document.getElementById('loginUsername').value = remembered;
            document.getElementById('rememberMe').checked = true;
          }
        }
      } catch (e) { console.warn('checkSession error', e); }

      document.getElementById('loginForm').addEventListener('submit', handleLogin);
      document.getElementById('togglePassword').addEventListener('click', togglePasswordVisibility);

      document.getElementById('logoutBtn').addEventListener('click', function() {
        if (confirm('Are you sure you want to logout?')) {
          logoutUser();
          showToast('Logged out successfully', 'info');
        }
      });

      document.getElementById('menuToggle').addEventListener('click', function() {
        document.getElementById('sidebar').classList.toggle('open');
      });

      document.addEventListener('click', function(e) {
        if (e.target.classList.contains('modal-overlay')) e.target.remove();
      });

      document.addEventListener('click', function(e) {
        const sidebar = document.getElementById('sidebar');
        const menuToggle = document.getElementById('menuToggle');
        if (window.innerWidth <= 768 && sidebar.classList.contains('open') &&
            !sidebar.contains(e.target) && !menuToggle.contains(e.target)) {
          sidebar.classList.remove('open');
        }
      });
    });

    /* Expose globals for inline handlers */
    window.navigateTo = navigateTo;
    window.setPosMode = setPosMode;
    window.setPaymentMethod = setPaymentMethod;
    window.updateRefillSize = updateRefillSize;
    window.updateCustomLiters = updateCustomLiters;
    window.updateRefillLiters = updateRefillLiters;
    window.addRefillToCart = addRefillToCart;
    window.addProductToCart = addProductToCart;
    window.updateCartQty = updateCartQty;
    window.removeFromCart = removeFromCart;
    window.completeSale = completeSale;
    window.closeModal = closeModal;
    window.printReceipt = printReceipt;
    window.showAddProductModal = showAddProductModal;
    window.addProduct = addProduct;
    window.showAdjustStockModal = showAdjustStockModal;
    window.adjustStock = adjustStock;
    window.updateFilter = updateFilter;
    window.exportReport = exportReport;
    window.saveSettings = saveSettings;
    window.confirmResetDemo = confirmResetDemo;
    window.renderReports = renderReports;
  </script>
</body>
</html>
